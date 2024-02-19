## 防腐层 Anticorruption Layer

*在设计良好的限界上下文与合作团队之间进行集成时，转换层会是简洁，甚至优雅的。但是，当控制或沟通不足以实现共享内核、供求式开发关系时，转换就会更加复杂。转换层会更加注重防御性。*

当下游系统需要通过上游系统的一个很大的接口进行集成时，这可能最终会完全掩盖下游模型原先的设计意图，导致其被迫修改得十分类似于上游系统的模型。遗留系统的模型通常很薄弱（如果不是大泥球的话），即使在例外情况下，遗留系统设计得很清晰，也可能不符合当前项目的需要，因此下游无法与上游模型保持一致。然而，对于下游项目来说，这种集成可能非常有价值，甚至是必需的。

因此：

**作为下游的客户端，创建一个隔离层，根据本系统的领域模型为自身提供上游系统的功能。该层通过上游系统现有的接口与其对话，几乎不需要修改上游系统。在内部，该层根据需要在两个模型之间进行单向或双向转换**。


