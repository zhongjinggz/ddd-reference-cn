## 合作关系 Partnership 

*当处于两个上下文中的团队成败与共时，往往会出现一种合作关系。*

如果两个相互依赖的上下文中的子系统协调不力，会导致两个项目都无法交付。一个系统中缺少的关键功能可能会导致另一个系统无法交付。如果接口不能满足另一子系统开发人员的期望，则可能导致集成失败。即使是共同商定的接口，也可能在后来发现使用不便，从而导致客户端系统开发缓慢；或者因为难以实现而阻碍服务端子系统的开发。任何一方的失败，都会导致两个项目共同失败。

因此：

**如果两个上下文中任何一个开发失败都会导致两者共同的交付失败，则负责这两个上下文的团队应建立合作关系。应建立一个流程来协调开发计划，并且共同管理两者之间的集成。**

**两个团队必须协调接口的演进，以满足两个系统的开发需要。相互依赖的功能应安排在同一发布版本中完成。**

在多数情况下，开发人员没有必要详细了解另一子系统的模型，但必须与另一个团队协调项目计划。当其中一个上下文的开发遇到障碍时，就需要共同对问题进行研究，以便找到一个快速解决问题的设计方案，同时又不会对各自的上下文产生太大的不良影响。

此外，还需要一个明确的流程来管理集成工作。例如，可以专门定义一个测试套件，以确保接口能够满足客户端系统的期望，该套件可以作为服务端系统上持续集成的一部分来运行。