## 值对象 Value Objects 


Some objects describe or compute some characteristic of a thing. 
一些对象是用于描述或计算一个事物的某些特征（characteristic）的。 

Many objects have no conceptual identity. 


Tracking the identity of entities is essential, but attaching identity to other objects can hurt system performance, add analytical work, and muddle the model by making all objects look the same. Software design is a constant battle with complexity. We must make distinctions so that special handling is applied only where necessary. 
However, if we think of this category of object as just the absence of identity, we haven’t added much to our toolbox or vocabulary. In fact, these objects have characteristics of their own, and their own significance to the model. These are the objects that describe things.  Therefore: 
When you care only about the attributes and logic of an element of the model, classify it as a value object. Make it express the meaning of the attributes it conveys and give it related functionality.  Treat  the  value  object  as  immutable.  Make  all  operations  Side-effect-free Functions that don’t depend on any mutable state. Don’t give a value object any identity and avoid the design complexities necessary to maintain entities.  

 


许多物体没有概念上的同一性。

跟踪实体的标识是必要的，但是将标识附加到其他对象会损害系统性能，增加分析工作，并使所有对象看起来都一样，从而使模型混乱。软件设计是一场与复杂性的持久战。我们必须加以区分，以便只有在必要时才进行特殊处理。

然而，如果我们认为这类对象仅仅是身份的缺失，那么我们的工具箱或词汇表中就没有增加多少东西。其实，这些对象都有自己的特点，对模型也有自己的意义。这些是描述事物的对象。因此:

当您只关心模型元素的属性和逻辑时，将其分类为值对象。让它表达它所传达的属性的含义，并赋予它相关的功能。将值对象视为不可变的。使所有操作都成为无副作用的函数，不依赖于任何可变状态。不要给值对象任何标识，避免维护实体所必需的设计复杂性。













分析。

因此： 

**结论。**

补充。
