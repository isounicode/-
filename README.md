# -

计算机安全
这里讨论的计算机，指的是计算机信息系统，是由计算机及相关的设备、设施（含网络）构成的，按照一定的应用目标和规则对信息进行采集、加工、存储、传送、检索等处理的人机系统。
计算机安全也叫做计算机信息系统安全。按照国际标准组织对计算机安全的定义，为处理数据系统所采取的技术和管理等安全保护，保护计算机的硬件、软件、数据不因偶然的或者恶意的原因而遭到破坏、更改、显露。
计算机安全管理的属性有可用性、可靠性、完整性、保密性、不可抵赖性、可审查性等。计算机安全包括实体安全、运行安全、信息安全及人员安全。
1、实体安全
计算机系统实体是指计算机系统的硬件部分，应包括计算机本身的硬件和各种接口、各种相应的外部设备、计算机网络的通讯设备、线路和信道等。
计算机实体安全是指为了保证计算机信息系统安全可靠运行，确保在对信息进行采集、处理、传输和存储过程中，不致受到人为或自然因素的危害，而使信息丢失、泄密或破坏，对计算机设备、设施(包括机房建筑、供电、空调等)、环境、人员等采取适当的安全措施。计算机实体安全是防止对信息威胁和攻击的第一步，也是防止对信息威胁和攻击的天然屏障，是基础。主要包括以下内容：
环境安全
主要是对计算机信息系统所在环境的区域保护和灾难保护。要求计算机场地要有防火、防水、防盗措施和设施，有拦截、屏蔽、均压分流、接地防雷等设施;有防静电、防尘设备，温度、湿度和洁净度在一定的控制范围等等。
设备安全
主要是对计算机信息系统设备的安全保护，包括设备的防毁、防盗、防止电磁信号辐射泄漏、防止线路截获;对UPS、存储器和外部设备的保护等。
媒体安全
主要包括媒体数据的安全及媒体本身的安全。目的是保护媒体数据的安全删除和媒体的安全销毁，防止媒体实体被盗、防毁和防霉等。
2、运行安全
系统的运行安全是计算机信息系统安全的重要环节，因为只有计算机信息系统的运行过程中的安全得到保证，才能完成对信息的正确处理，达到发挥系统各项功能的目的。包括系统风险分析、审计跟踪、备份与恢复、应急处理四个方面内容。
风险分析
风险分析是指评估威胁发生的可能性、系统受到攻击的脆弱性和潜在的损失，其最终目的是帮助选择安全防护并将风险降低到可接受的程度。
计算机信息系统在设计前和运行前需要进行静态分析，旨在发现系统的潜在安全隐患;其次对系统进行动态分析，即在系统运行过程中测试，跟踪并记录其活动，旨在发现系统运行期的安全漏洞;最后是系统运行后的分析，并提供相应的系统脆弱性分析报告。
常见的风险有后门/陷阱门、犯大错误、拒绝使用、无法使用、伪造、故意对程序或数据破坏、逻辑炸弹、错误传递、计算机病毒和超级处理等。常见分析工具有自动风险评估系统ARESH、Bayesian判决辅助系统、Livermore风险分析法等。
审计跟踪
审计跟踪是一种保证计算机信息系统运行安全的常用且有效的技术手段。利用审计跟踪，对计算机信息系统工作过程进行详尽的审计跟踪，记录和跟踪各种系统状态的变化（如用户使用系统的时间和日期及操作，对程序和文件的使用监控等），以保存、维护和管理审计日志，实现对各种安全事故的定位。
备份与恢复
备份与恢复是对重要的系统文件、数据进行备份，且备份放在异处，甚至对重要设备也有备份，以确保在系统崩溃或数据丢失后能及时准确进行恢复，保障信息处理操作仍能进行。可采取磁盘镜像、磁盘冗余阵列等技术。
应急处理
应急处理主要是在计算机信息系统受到损害、系统崩溃或发生灾难事件时，应有完善可行的应急计划和快速恢复实施应急措施，基本做到反应紧急、备份完备和恢复及时，使系统能正常运行，以尽可能减少由此而产生的损失。
3、信息安全
计算机信息系统的信息安全是核心，是指防止信息财产被故意或偶然的泄漏、更改、破坏或使信息被非法系统辨识、控制，确保信息的保密性、完整性、可用性和可控性。针对计算机信息系统中的信息存在形式和运行特点，信息安全可分为操作系统安全、数据库安全、网络安全、病毒防护、访问控制和加密。
操作系统安全
操作系统安全是指操作系统对计算机信息系统的硬件和软件资源进行有效控制，对程序执行期间使用资源的合法性进行检查，利用对程序和数据的读、写管理，防止因蓄意破坏或意外事故对信息造成的威胁，从而达到保护信息的完整性、可用性和保密性。
操作系统安全可通过用户认证、隔离、存取控制及完整性等几种方法来实现。用户认证就是系统有一个对用户识别的方法，通过用户名和口令实现，口令机制有口令字、IC卡控制、指纹鉴别和视网膜鉴别等。
隔离技术是在电子数据处理成份的周围建立屏障，以使该环境中实施存取规则，可通过物理隔离、时间隔离、逻辑隔离和密码技术隔离来实现。
存取控制是对程序执行期间访问资源的合法性进行检查，并通过控制对数据和程序的读、写、修改、删除和执行等操作进行保护，防止因事故和有意破坏造成对信息的威胁。系统完整性涉及到程序和数据两方面，程序完整性要在整个程序设计活动中严格控制;数据完整性由错误控制进行保护。
数据库安全
数据库系统中的数据的安全性包括:完整性——只有授权用户才能修改信息，不允许用户对信息进行非法修改;可用性——当授权用户存取其有权使用的信息时，数据库系统一定能提供这些信息;保密性——只有授权用户才能存取信息。
实现数据库安全可通过用户认证、身份鉴别、访问控制和数据库内外加密等方法来实现。用户认证通过在操作系统用户认证基础上，要求用户对通行字、日期和时间检查认证。身份鉴别是数据库系统具备的独立的用户身份鉴别机制。
访问机制，运用安全级元素的确定、视图技术等方法，确保用户仅能访问已授权的数据，并可保证同一组数据的不同用户被授予不同访问权限。
数据库外加密是操作系统完成的，如采用文件加密方法等，把数据形成存储块送入数据库；数据库内加密是对数据库以数据元素、域或记录形式加密，常用加密方法有DES加密、子密钥数据库加密和秘密同态加密技术等。
访问控制
访问控制是系统安全机制的核心，对处理状态下的信息进行保护，对所有直接存取活动进行授权;同时，对程序执行期间访问资源的合法性进行检查，控制对数据和程序的读、写、修改、删除、执行等操作，防止因事故和有意破坏对信息的威胁，主要包括授权、确定存取权限和实施权限三个内容。
通过最小授权、存取权分离、实体权限的时效性和对存取访问的监督检查、访问控制表、访问控制矩阵和能力表等方法来实现。
加密技术
计算机数据信息的加密基本上属于通信加密的类型，但又不同于一般的通信保密技术，被加密的明文往往是程序或其他处理的原始数据或是运行结果，而形成的密文是静态的，一般不是执行中的程序，仅用以存储或作为通信输出。
一般密码系统包括明文、密文、加密、解密和密钥五部分，常见密码加密有换位加密、矩阵移位加密、定长置换加密、替代密码和DES加密、RAS加密、PKI和MD5等算法。
网络安全
信息交换是计算机网络信息系统存在的基础。
在网络环境中，增加了用户之间的互相不信任和信息存储、传输、处理中被网络攻击的风险。网络攻击包括被动攻击和主动攻击。被动攻击指一切截取的攻击，典型的攻击方式是网络窃听、流量分析和破译，通过截取数据包或流量分析，从中窃取重要的敏感信息，通过破译窃取他人的机密。主动攻击最主要的方法就是对信息进行修改，比如对信息的内容进行更改、删除、添加；改变信息的源或目的地；改变报文分组的顺序或将同一报文反复;篡改回执等。
为了保障计算机网络中的信息安全，拒绝非法用户使用系统资源和防止非法用户窃听、破坏系统资源，就必须进行访问控制。访问控制的主要方式有身份认证、报文验证、数字签名、防火墙。

病毒防护
计算机病毒是指编制或者在计算机程序中插入的破坏计算机功能或者毁坏数据，影响计算机使用，并能自我复制的一组计算机指令或程序代码。其本质是一种具有自我复制能力的程序，具有复制性、传播性和破坏性。
计算机病毒不同于生物医学上的“病毒”，计算机病毒不是天然存在的，是人故意编制的一种特殊的计算机程序。计算机病毒对信息系统有极大的危害性，轻者可以增加系统开销，降低系统工作效率;重者可使程序、数据丢失，甚至系统崩溃，无法工作，更甚者造成计算机主板毁坏，如CIH病毒等。
