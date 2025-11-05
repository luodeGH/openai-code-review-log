基于提供的Git diff记录，以下是对代码变更的评审：

1. **IIndexGroupBuyMarketService.java 和 IndexGroupBuyMarketServiceImpl.java**
   - **变更**: 两个文件中的作者注释被移除。
   - **评审**: 移除作者注释可能会导致代码的可追溯性降低。建议保留作者信息，以便于追踪代码的修改历史和责任归属。

2. **AbstractDiscountCalculateService.java**
   - **变更**: 类注释中的作者信息被移除。
   - **评审**: 同上，建议保留作者信息。

3. **IDiscountCalculateService.java**
   - **变更**: 类注释中的作者信息被移除。
   - **评审**: 同上，建议保留作者信息。

4. **MJCalculateService.java, NCalculateService.java, ZJCalculateService.java, ZKCalculateService.java**
   - **变更**: 类注释中的作者信息被移除。
   - **评审**: 同上，建议保留作者信息。

5. **AbstractGroupBuyMarketSupport.java, DefaultActivityStrategyFactory.java, EndNode.java, ErrorNode.java, MarketNode.java, MarketNode2CompletableFuture.java, RootNode.java, SwitchNode.java, TagNode.java, QueryGroupBuyActivityDiscountVOThreadTask.java, QuerySkuVOFromDBThreadTask.java**
   - **变更**: 多个类和任务类中的作者信息被移除。
   - **评审**: 同上，建议保留作者信息。

6. **DCCService.java**
   - **变更**: 缓存开启开关的说明从“true为开启，1为关闭”更改为“1为开启，0为关闭”。
   - **评审**: 变更注释以反映实际的代码行为是好的实践，这有助于未来的维护者理解代码。

7. **GitCommand.java**
   - **变更**: diff()方法中的注释被添加，说明如何获取最新提交的ID和比较结果。
   - **评审**: 添加注释以解释代码的作用是好的实践，这有助于其他开发者理解代码。

8. **ChatGLM.java**
   - **变更**: 类注释中的作者信息被移除，并添加了额外的空行。
   - **评审**: 建议保留作者信息，并移除不必要的空行。

总体来说，这些变更主要是关于代码注释的修改，建议保留作者信息以提高代码的可追溯性和可维护性。