## 实体 Entities

（进行中）
Many objects represent a thread of continuity and identity, going through a lifecycle, though their attributes may change. 

Some objects are not defined primarily by their attributes. They represent a thread of identity that runs through time and often across distinct representations. Sometimes such an object must  be  matched  with  another  object  even  though  attributes  differ.  An  object  must  be distinguished from other objects even though they might have the same attributes. Mistaken identity can lead to data corruption. 

Therefore: 

When an object is distinguished by its identity, rather than its attributes, make this primary to its definition in the model. Keep the class definition simple and focused on life cycle continuity and identity.  

Define a means of distinguishing each object regardless of its form or history. Be alert to requirements  that  call  for  matching  objects  by  attributes.  Define  an  operation  that  is guaranteed to produce a unique result for each object, possibly by attaching a symbol that is guaranteed unique. This means of identification may come from the outside, or it may be an arbitrary identifier created by and for the system, but it must correspond to the identity distinctions in the model.  

The model must define what it means to be the same thing. 

(aka Reference Objects)   
很多对象表示的是在生命周期中具有连续性和同一性的事物，尽管在生命周期中对象的属性可能发生改变。

有些对象主要不是由它们的属性来定义的。这些对象所代表的事物，可以贯穿一段时间，常常具有不同表现形式，但仍保持同一性。有时，即使属性不同，两个对象也要视为同一个事物。另一方面，即使属性都相同，一个对象也要与另一个对象视为不同的事物。搞错同一性可能会破坏数据。

因此:

**当一个对象由表示同一性的标识而不是属性，与其他对象相区别时，在模型中应以标识为主来定义该对象。使类定义保持简单，将关注点放在生命周期的连续性和同一性上。**  

**定义一种方法来区分每个对象，而不管其形式或历史。警惕那些通过属性来匹配对象的需求。定义一个保证为每个对象产生唯一结果的操作，可以通过附加一个保证唯一的符号来实现。这种识别方法可能来自外部，或者它可能是由系统创建并为系统创建的任意标识符，但是它必须与模型中的标识符区别相对应。**  

**模型必须定义相同事物的含义。**

又名“引用对象”（Reference Objects）

**译者注：** 英文中 Identity 可翻译为 “同一性”、“身份”或“标识”等。这几个词义是相关关联的，一个人的“身份”就表达了这个人的“同一性”，而表示身份的“身份证号”则是这个人的“表标识”。汉语中没有一个词汇同时表达这几种意思。因此本文中根据上下文，有时译作“同一性”，有时译作“标识”，有时译作“标识同一性的标识”。


分析。

因此： 

**结论。**

补充。
