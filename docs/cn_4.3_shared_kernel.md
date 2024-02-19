## 共享内核 Shared Kernel

*对模型的某个部分及其相关代码进行共享会导致非常紧密的相互依赖关系。这种关系既可能有利于设计工作，也可能对其造成破坏。*

对于一个大型上下文，如果不能很好地进行功能集成，那么对它进行持续集成可能会造成过高的开销。当团队不具备保障持续集成的技能或行政组织，或者只有一个庞大而笨重的团队时，情况尤其如此。

因此，需要划分不同的限界上下文并组建多个团队。

一旦划分成不同的团队，当他们共同开发密切相关的应用时，如果不进行协调，那么在短期内或许会快速推进，但他们的产出物可能无法组装在一起。即使团队之间可以合作，最终也可能在转换层和程序改造上花费大量精力，同时还会造成重复劳动，并失去统一语言所带来的好处。

因此：

**在领域模型中，指定各团队同意共享的某个子集，这个子集要具有明确的边界。应保持这个内核的精简。**

**在此边界内，还要包括与该模型子集相对应的代码子集以及数据库设计的子集。这些明确共享的内容具有特殊的地位，在没有和其他团队协商的情况下，不能擅自更改。**

定义一个持续集成流程，使内核模型保持紧密，并与各团队的统一语言保持一致。功能系统要频繁地集成，但集成频率应略低于团队内部的持续集成。