## 作业1

### 简答题

#### 1、软件工程定义
软件工程是一门研究用工程化方法构建和维护有效的、实用的和高质量的软件的学科。

#### 2、软件危机的原因，表现以及解决方法
##### 软件危机的原因：
* 用户需求不明确，主要有4个方面：用户自己不清楚需要的功能是什么，用户对功能的描述不准确，开发过程中用户要求增加删改功能，以及开发人员对于用户需求的理解与用户本来愿望有偏差

* 缺乏正确的理论指导，即缺少有力的方法学和工具等。

* 软件开发规模越来越大

* 软件开发复杂度越来越高

##### 软件危机的表现：
* 软件开发进度难以预测
* 软件开发成本难以控制
* 用户对产品功能难以满足
* 软件产品质量无法保证
* 软件产品难以维护
* 软件缺少适当的文档资料

##### 软件危机的解决途径：
借鉴硬件工程和其他人类工程成功的经验，提出软件生命周期模型，以期达到降低软件生产成本 、改进软件产品质量、提高软件生产率水平，进而降低软件危机的发生概率。

#### 3、软件生命周期
软件生命周期(SDLC，Systems Development Life Cycle,SDLC)是软件的产生直到报废或停止使用的生命周期，周期内有问题定义、可行性分析、总体描述、系统设计、编码、调试和测试、验收与运行、维护升级到废弃等阶段。

#### 4、SWEBoK 的 15 个知识域（An Overview of the SWEBOK Guide 请中文翻译其名称与简短说明）

##### Knowledge Areas Characterizing the Practice of Software Engineering 用于描述软件工程实践的知识域

##### 1）Software Requirements 软件需求
软件要求KA关注软件需求的启发，协商，分析，规范和验证。软件需求表达了对软件产品的需求和限制，这些需求和约束有助于解决一些现实问题。

##### 2）Software Design 软件设计
软件设计KA涵盖了设计过程和最终产品。其中，软件设计过程是软件工程生命周期活动，而软件设计（结果）则必须描述软件体系结构，即软件如何分解成各个组件，再由各个组件组织为一体，以及这些组件之间的接口。

##### 3）Software Construction 软件构建
软件构建是指通过结合详细设计，编码，单元测试，集成测试，调试和验证来详细地构建软件。该KA涵盖了软件构建基础，软件管理构建，构建技术，实际性考虑和软件构建工具。

##### 4）Software Testing 软件测试
软件测试主要指在有限的测试用例集上针对预期行为动态验证程序的行为。软件测试KA包括软件测试的基础知识，测试技术，人机界面测试与评估，测试相关的方法和实际性考虑。

##### 5）Software Maintenance 软件维护
软件维护包括增强现有功能，调整软件以在新的和修改的操作环境中运行以及修复缺陷。软件维护KA包括软件维护的基础知识（维护必要性，维护类别，维护成本），软件维护中的关键问题（技术问题，管理问题，维护成本预算，软件维护测量），维护过程; 软件维护技术（程序理解，重新设计，逆向工程，重构，软件退休），灾难恢复技术和软件维护工具。

##### 6）Software Configuration Management 软件配置管理
系统配置指的是硬件、固件、软件或是这些结合的功能和/或物理特征。软件配置管理（SCM）是在不同时间点识别系统配置的规则，用于系统地掌握配置的改变，以及在整个软件生命周期中维持配置的完整性和可追溯性。软件配置管理KA涵盖SCM过程的管理，软件配置识别、控制、状态核算、审计，软件发布管理和交付以及配置管理工具。

##### 7）Software Engineering Management 软件工程管理
软件工程管理包括规划，协调，测量，报告和项目/程序控制，以确保软件的开发和维护是系统化的，规范化的和量化的。

##### 8）Software Engineering Process 软件工程过程
软件工程KA关注软件生命周期过程的定义，实施，评估，测量，管理和改进。

##### 9）Software Engineering Models and Methods 软件工程模型和方法
软件工程模型和方法KA说明了围绕多个生命周期阶段的方法，而围绕某个特定的软件生命周期阶段的方法则包含在其他KA中。

##### 10）Software Quality 软件质量
软件质量KA包括软件质量的基础知识（软件工程文化，软件质量特征，软件质量的价值和成本以及软件质量改进），软件质量管理流程（软件质量保证、验证和确认，复查和审核），和实际性考虑（缺陷表征，软件质量测量和软件质量工具）。

##### 11）Software Engineering Professional Practice 软件工程专业实践
软件工程专业实践关注为以一个专业的、负责任的以及有基本道德修养的方式进行软件工程实践，一个软件工程师必须具备的专业知识、技能和职业态度。

##### Knowledge Areas Characterizing the Educational Requirements of Software Engineering 用于描述软件工程教育要求的知识域

##### 1）Software Engineering Economics 软件工程经济学
软件工程经济学KA关注的是在业务环境中做出决策，以使技术决策与企业的业务目标保持一致。

##### 2）Computing Foundations 计算机基础
计算基础KA涵盖了提供软件工程实践所需的计算机背景的基础主题。涵盖的主题包括问题解决方法，抽象，算法和复杂性，编程基础，并行和分布式计算的基础，计算机组成，操作系统和网络通信。

##### 3）Mathematical Foundations 数学基础
数学基础KA涵盖了提供软件工程实践所必需的数学背景的基础主题。涵盖的主题包括集合，关系和函数，基本命题和谓词逻辑，证明方法，图形和树; 离散概率，语法和有限状态机以及数论。

##### 4）Engineering Foundations 工程基础
工程基础KA涵盖了提供软件工程实践所必需的工程背景的基础主题。涵盖的主题包括经验方法和实验技术，统计分析，测量和指标，工程设计，仿真与建模和根本原因分析。

#### 5、简单解释 CMMI 的五个级别
`CMMI`全称是`Capability Maturity Model Integration`，即软件能力成熟度模型集成模型，分为5个级别:

##### 1）初始级
软件过程杂乱无章，甚至混乱，且不可确定的和不可预见的。常做出过分的承诺。成功完全依赖个人努力和杰出的专业人才，取决于超常的管理人员和杰出有效的软件开发人员。

##### 2）已管理级
进行较为现实的求诺，建立了基本的项目管理过程来跟踪成本、进度和功能。定义了软件项目的标准，并相信它，遵循它。通过于合同建立有效的供求关系。

##### 3）已定义级
无论管理方面或工程方面的软件过程都已文件化、标准化，并综合成软件开发组织的标准软件过程。在从事一项工程时，产品的生产过程、花费、计划以及功能都是可以完全控制的，从而软件质量也可以控制。

##### 4）量化管理级
制定了软件过程和产品质量的详细而具体的度量标准。组织的度量工程保证所有项目对生产率和质量进行度量，并作为重要的软件过程活功。在开发组织内已建立软件过程数据库，保存收集到的数据，可用于各项目的软件过程。

##### 5）优化管理级
整个组织特别关注软件过程改进的持续性、顶见及增强自身。防止缺陷及问题的发生。不断地提高他们的过程能力。组织能找出过程的不足并预先改进。

#### 6、用自己语言简述 SWEBok 或 CMMI
软件知识体系（Software Engineering Body of Knowledge）是IEEE计算机学会职业委员会主持的一个项目，其目标为促进世界范围内对软件工程的一直观点；阐明软件工程相对于其他学科的位置，并确定它们的分界；刻画软件工程学科的内容；提供使用知识体系的主题并为开发课程和个人认证与许可资料提供一个基础。SWEBoK共提出了15个知识域，其中11个用于描述软件工程实践的特点，指出了软件工程实践时需要注意的问题，包括软件需求，软件设计，软件构建，软件测试，软件维护，软件配置管理，软件工程管理，软件工程过程，软件工程模型和方法，软件质量和软件工程专业实践，从软件周期的各个阶段以及整体提出了软件工程师需要掌握的技能和职业素养。而另外4个知识域则是用于描述软件工程教育的要求，主要从软件工程经济学，计算机基础，数学基础和工程基础4个方面对为了培养软件工程师而开设的软件工程专业指明了教育方向。