## 柔性设计 Supple Design

要想加快项目的开发速度，而不是被其自身的遗留问题所拖累，项目就要具有易于参与、拥抱变化的设计，也就是所谓柔性设计。

柔性设计是深度建模的补充。

开发人员会扮演两种不同的角色，设计必须满足这两种角色的要求。同一个人可以很好地扮演这两种角色，甚至在几分钟内来回切换，但不同的角色与代码的关系还是不同的。

其中一种角色是模型客户端程序的开发人员，他们利用领域层所设计的能力，在应用层代码或另一个领域的领域层代码中调用领域对象。柔性设计深入地揭示了底层模型，使模型具有内在的清晰性。客户端开发人员可以使用一组极简的松耦合概念来灵活地表达领域中的各种场景。设计元素自然地组合在一起，从而得到可预测、清晰易懂而又稳健的设计。

同样重要的是，设计也必须服务于另一种角色，也就是从事改变领域设计本身的开发人员。为了容易修改，设计必须易于理解，揭示出和客户端开发人员的理解相同的底层模型。设计必须遵循深层领域模型的[轮廓](cn_3.8_conceptual_contours.md)，从而使多数变更都可以在扩展点上灵活修改。相应代码所产生的效果（effect）必须是显而易见的，从而容易预期设计变更的后果。


- 让行为清晰易见
- 降低变更成本
- 创建易于开发人员参与的软件







