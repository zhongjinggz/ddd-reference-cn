# 领域驱动设计参考—定义及模式提要 
 ["Domain-Driven Design Reference"](http://domainlanguage.com/wp-content/uploads/2016/05/DDD_Reference_2015-03.pdf) 中文版  
作者：Eric Evans  
译者：钟敬

【译者注】

- Eric Evans 在2004年出版了《领域驱动设计》一书。2014年，作者抽取出书中各模式的摘要，并增补了一些内容，成为了这本小册子。通过阅读本书可以达到以下目的：
  - 对于不了解DDD的读者，可以大体上了解DDD内容；
  - 对于熟悉DDD的读者，可以印证自己的知识结构是否准确和完整；
  - 对于培训师、咨询师、有关书籍的作者等，可以在相关工作中校准概念，并在此基础上进一步扩展。
- 电子书地址 https://zhongjinggz.github.io/ddd-reference-cn/

## 目录 Contents

[致谢 Acknowledgements](cn_0.1_acknowledgement.md)  
[定义 Definitions](cn_0.2_definitions.md)  
[模式语言总览 Pattern Language Overview](cn_0.3_pattern_language_overview.md)  

### [I. 运用模型 Putting the Model to Work](cn_1.0_putting_the_model_to_work.md)  

[1.1 限界上下文 Bounded Context](cn_1.1_bounted_context.md)  
[1.2 统一语言 Ubiquitous Language](cn_1.2_ubiquitous_language.md)  
[1.3 持续集成 Continuous Integration](cn_1.3_continuous_integration.md)  
[1.4 模型驱动设计 Model‐Driven Design](cn_1.4_model_driven_design.md)  
[1.5 实操型建模师 Hands‐on Modelers](cn_1.5_hands_on_modlers.md)  
[1.6 通过重构加深理解 Refactoring Toward Deeper Insight](cn_1.6_refactoring_toward_deeper_insight.md)  

### [II. 模型驱动设计的构建块 Building Blocks of a Model-Driven Design](cn_2.0_building_blocks_of_a_model_driven_design.md)  

[2.1 分层架构 Layered Architecture](cn_2.1_layered_architecture.md)  
[2.2 实体 Entities](cn_2.2_entities.md)  
[2.3 值对象 Value Objects](cn_2.3_value_objects.md)  
[2.4 领域事件 Domain Events *](cn_2.4_domain_events.md)  
[2.5 服务 Services](cn_2.5_services.md)       
[2.6 模块 Modules](cn_2.6_modules.md)       
[2.7 聚合体 Aggregates](cn_2.7_aggregate.md)   
[2.8 仓库 Repositories](cn_2.8_repositories.md)   
[2.9 工厂 Factories](cn_2.9_factories.md)   

### [III. 柔性设计 Supple Design](cn_3.0_supple_design.md)

[3.1 揭示意图的接口 Intention-Revealing Interfaces](cn_3.1_intention_revealing_interfaces.md)  
[3.2 无副作用函数 Side-Effect-Free Functions](cn_3.2_side_effect_free_functions.md)  
[3.3 断言 Assertions](cn_3.3_assertions.md)  
[3.4 独立类 Standalone Classes](cn_3.4_standalone_classes.md)  
[3.5 操作闭包 Closure of Operations](cn_3.5_closure_of_operations.md)  
[3.6 声明式设计 Declarative Design](cn_3.6_declarative_design.md)  
[3.7 借鉴既有的形式系统 Drawing on Established Formalisms](cn_3.7_drawing_on_established_formalisms.md)  
[3.8 概念轮廓 Conceptual Contours](cn_3.8_conceptual_contours.md)

### IV. 战略设计之上下文映射 Context Mapping for Strategic Design  

4.1 上下文映射 Context Map  
4.2 伙伴关系 Partnership *  
4.3 共享内核 Shared Kernel  
4.4 客户/供应商开发 Customer/Supplier Development   
4.5 尊奉者 Conformist  
4.6 防腐层 Anticorruption Layer   
[4.7 开放主机服务 Open‐host Service](cn_4.7_open_host_service.md)  
[4.8 发布语言 Published Language](cn_4.8_published_language.md)  
4.9 彼此独立 Separate Ways  
4.10 大泥球 Big Ball of Mud *  

### [V. 战略设计之精炼 Distillation for Strategic Design](cn_5.0_distillation_for_strategic_design.md)  

[5.1 核心域 Core Domain](cn_5.1_core_domain.md)  
[5.2 通用子域 Generic Subdomains](cn_5.2_generic_subdomains.md)
[5.3 领域愿景声明 Domain Vision Statement](cn_5.3_domain_vision_statement.md)  
[5.4 强调核心 Highlighted Core](cn_5.4_Highlighted%20Core.md)  
[5.5 内聚实现机制 Cohesive Mechanisms](cn_5.5_cohesive_mechanisms.md)  
[5.6 隔离核心 Segregated Core](cn_5.6_segregated_core.md)  
[5.7 抽象核心 Abstract Core](cn_5.7_abstract_core.md)   

### [VI. 战略设计之大型结构 Large-scale Structure for Strategic Design](cn_6.0_large_scale_structure.md)

[6.1 演进式秩序 Evolving Order](cn_6.1_evolving_order.md)  
[6.2 系统隐喻 System Metaphor](cn_6.2_system_metaphor.md)  
[6.3 职责分层 Responsibility Layers](cn_6.3_responsibility_layers.md)  
[6.4 知识层 Knowledge Level](cn_6.4_knowledge_level.md)  
[6.5 可插拔组件框架 Pluggable Component Framework](cn_6.5_pluggable_component_framework.md)  

\* 自2004年的书之后引入的新术语。  
