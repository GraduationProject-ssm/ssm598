# [首页查询更多项目](https://github.com/GraduationProject-ssm) 包安装运行


# ssm598基于VUE3+SSM框架的在线宠物商城+vue

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1t58veLEnL?p=193)


# 第1章 绪论
## 1.1 研究背景
互联网概念的产生到如今的蓬勃发展，用了短短的几十年时间就风靡全球，使得全球各个行业都进行了互联网的改造升级，标志着互联网浪潮的来临。在这个新的时代，各行各业都充分考虑互联网是否能与本行业进行结合，是否能解决本行业或者本行业中某些方面的自古以来的痛点。长期以来，数据内容，数据传播，数据储存等都是一门门专业的内容，因为需要记住的内容很多，造成古人的言简意赅，如今互联网的到来让数据更加的清晰好认不复杂，一目了然不出错，毕竟在整个历史上数据的丢失，传承的断代，都是因为数据不能好好的保存，不能好好的流传。当年的年代用互联网思维和互联网技术，对大量数据的录入更新，存储汇总，备份分析方面，使得远远的超过传统的数据管理技术。在这样的时代潮流下，采用新技术开发新软件，对传统行业进行革命性的改造成为了当今的主流。本次开发在线宠物商城，解决了宠物信息管理关于数据方面的管理分析，存储传输的痛点，不仅仅对管理员提供了便利，还能提高用户的满意度。
## 1.2目的和意义
此次在线宠物商城的开发，需要用到的知识不仅涉及到界面设计与功能设计方面的知识，还需要涉及到数据库与编程语言上面的知识，这些知识点对于一个即将毕业的学生来说，一是为了巩固在校所学相关专业知识；二是为了让学生学会如何将专业理论知识运用于现实软件的开发过程；三是让学生明白知识是无穷无尽的，要时刻明白活到老学到老的真正含义，让学生要养成时刻学习的习惯，同时也要相信通过此次程序的开发，会让学生对于专业知识的理解与软件开发水平的提高有着极大的帮助。
## 1.3 论文研究内容
论文设计的结构也是依照程序开发的流程进展的，也涉及到功能需求分析，功能设计与实现，程序测试等流程。

绪论：讲解课题的背景与意义，展示论文结构。

程序开发技术：讲解程序运用到的工具与技术知识。

系统分析：讲解程序的功能需求与开发可行性问题。

系统设计：讲解程序的功能与数据库的设计。

系统实现：讲解程序功能与界面实现。

系统测试：讲解程序的功能测试。
# 第2章 程序开发技术
## 2.1 Mysql数据库
开发的程序面向用户的只是程序的功能界面，让用户操作程序界面的各个功能，那么很多人就会问，用户使用程序功能生成的数据信息放在哪里的？这个就需要涉及到数据库的知识了，一般来说，程序开发通常就会对常用数据存储工具的特点进行分析比对，比如Mysql数据库的特点与优势，Access数据库的特点与优势，Sqlserver数据库的特点与优势等，最终看哪个数据库与需要开发的程序比较匹配，也符合程序功能运行需要的数据存储要求，比如，需要开发商业级别的程序，存储的数据对数据库要求较高，可以选用Oracle，如果只是比较简单的程序，对数据存储没有过多要求，可以选用微软旗下的Access，当开发程序要求数据库占用空间小，并能满足程序数据存储要求时，就可以考虑Oracle公司从瑞典MySQL AB公司在很早之前就收购过一个关系型数据库，它是现在的Mysql数据库。

为了更容易理解Mysql数据库，接下来就对其具备的主要特征进行描述。

（1）首选Mysql数据库也是为了节省开发资金，因为网络上对Mysql的源码都已进行了公开展示，开发者根据程序开发需要可以进行下载，并做一些改动就可以使用在程序中，可以推动开发者开发此程序的开发进度。

（2）SQL数据语言在Mysql里面也同样适用

（3）Mysql不仅可以支持多种编程语言，比如在校期间学到的C语言，Java语言，以及课后接触的PHP语言，C++语言等编程语言，它都能很好的支持，而且Mysql的安装与使用还不挑剔使用平台。

（4）Mysql可以支持具有千万条数据记录的数据库，电脑操作系统在进行首次安装或者是重装时，可以根据需要选择安装32位或64位操作系统，这两种操作系统对表文件的支持力度不一样，32位的操作系统最多可以存放4GB的表文件，64位操作系统最多可以存放8TB的表文件。

（5）Mysql数据库可以通过GPL协议进行个性化定制，需要开发者自己对数据库的源代码进行修改，以此开发出属于自己的Mysql。
## 2.2 Java语言
程序开发语言有很多，但是截至目前，Java语言在IT领域内，仍然是最被认可，以及被广泛运用的编写语言之一，因此在选择此程序的编写语言上，果断选择这门编程语言进行程序开发。可以说经过了这么多年的发展，Java语言不仅在Web开发领域有了突出性贡献，而且在大数据开发领域以及Android开发领域都得到了广泛运用。由于Java语言拥有较强的扩展性能，并且表现出的稳定性能，让其成为大型后端系统开发语言首选，现如今，Java语言也成为了一种常用的互联网平台的解决方案。

作为一种源码在网络上开源的面向对象的程序开发Java语言，由它开发完成的程序是不可能直接运行在各大平台的，Java程序的运行，需要在操作平台上配置其运行的环境，包括数据库软件与Java程序开发软件等工具的安装与配置。在Win7，Win10或其它操作平台上配置Java程序运行环境，只要环境配置成功，Java程序都可以运行起来。

# 第3章 系统分析
在进行系统分析之前，需要从网络上或者是图书馆的开发类书籍中收集大量的资料，因为这个环节也是帮助即将开发的程序软件制定一套最优的方案，一旦确定了程序软件需要具备的功能，就意味着接下来的工作和任务都是围绕着这个方案执行的，所以系统分析需要对程序功能反复进行思考和研究。
## 3.1可行性分析
开发一款系统软件之前，用户都会思考这个软件程序值不值得去开发，把开发软件过程中可能涉及到的问题罗列出来，并一个个分析解决，以此来确定开发这款程序软件是否有必要，这样的分析方法也能帮助用户降低损失，不至于开发者开发进度进行到一半之后，突然遇到问题就放弃对软件的开发，到那时，资金损失，人力投入等方面就损耗太大了。
### 3.1.1技术可行性分析
此次开发程序使用到的开发工具有：Eclipse，Mysql等工具，使用的开发语言是Java，选择的开发工具和开发语言都是在大学课堂接触并学习过，后期因为自己也比较感兴趣，所以也通过网络渠道，或借助图书馆的开发类书籍进行过软件开发知识的系统学习，让自己有了一定的知识积累，加上自己在校期间也独立开发过一些软件作品，也积累了一定的开发经验，所以这次毕设作品的制作在技术上无须担忧过多。
### 3.1.2经济可行性分析
目前的信息时代，对信息的管理趋于高效化，便捷化，这也是计算机大力普及所带来的便利，此程序软件在设备选用上，依靠的是比较大众的电脑设备，对电脑的配置没有过多要求，一般学校的计算机机房的电脑都可以满足程序开发需求，另外，开发出此款程序，让信息处理变得高效率，其所带来的高效益是远超程序开发的低成本的，因此程序开发的资金投入是可以忽略不计的。
### 3.1.3操作可行性分析
程序软件的操作界面是符合大众审美的需求，功能模块的布局也是类似于社会上同种类型的软件，因此使用者操作该软件可以无需培训就上手。加上现在计算机入驻各家各户，大部分人的计算机操作水平都比较高，这样的局面也表明开发出来的程序在操作性问题上也是不用担心的。

综合上面的可行性论证，基本可以确定程序开发完全可行。
## 3.2系统运行环境
程序经过编码可以实现对程序设计的功能。但是编码实现时需要一定的配置环境，包括了电脑上的硬件环境，也包括在电脑操作系统上安装的软件环境。

硬件环境：一台可以正常使用并能够上网的笔记本或者是电脑，电脑内存最低要求4个G，电脑的中央处理器可以配置i5CPU。

软件环境：运用的微软操作系统是比较稳定的win7旗舰版系统，采用比较熟练360安全浏览器，并在此系统上通过浏览器下载安装好Eclipse软件，下载安装好MYSQL软件等。
## 3.3系统流程分析
分析程序的流程，涉及到程序的整体操作流程，通过分析与设计，绘制的程序操作流程图见下图。此程序为了确保安全，会让使用者通过登录模块验证信息，符合要求的使用者才有权限操作程序。

![](/md/blog.001.png)

图3-1 程序操作流程图

程序处理数据会涉及到数据的录入环节，绘制的添加流程见下图。程序录入数据过程中，始终与数据库保持同步。

![](/md/blog.002.png)

图3-2 信息添加流程图

程序里面的数据也会出现错误，因此就有相应的修改数据的功能，绘制的程序修改流程见下图。此过程也是跟后台数据库进行数据同步显示。

![](/md/blog.003.png)

图3-3信息修改流程图

程序数据存放于数据仓库，有时也会涉及到数据删除，此过程对应的流程图见下图。数据信息被删除之后，数据库里面也就没有了该数据信息了。

![](/md/blog.004.png)

图3-4 信息删除流程图


# 第4章 系统设计
## 4.1 系统设计的原则
在系统设计过程中，也需要遵循相应的设计原则，这些设计原则可以帮助设计者在短时间内设计出符合设计规范的设计方案。设计原则主要有可靠性，安全性，可定制化，可扩展性，可维护性，可升级性以及客户体验等原则。下面就对这些原则进行简要阐述。

可靠性：一个软件是否可靠决定了其是否被用户使用，设计不可靠的软件，用户很容易就遗弃；

安全性：程序软件承担了信息的保存与管理等事务，安全性不足的软件会导致使用者承担巨大的损失；所以系统安全也是需要考虑进入的；

可定制化：市场环境从来都不是一直固定不变，面对客户群体的改变，以及使用环境的改变，市场需求的改变等因素，程序软件也要易于调整以适应各种变化；

可扩展性：程序软件在运行使用期间，也需要及时引进当下的新技术来进行系统优化，主要就是在系统功能层面，系统性能层面上进行相应的扩展，只有这样才能让系统在实际生活中继续占有市场；

可维护性：程序软件的维护需要一定量的资金，不管是排除现有程序错误，还是变更软件的现有需求，都需要在软件技术上投入一定资金，所以易于维护的软件程序就可以降低技术层面的资金消耗；

可升级性：程序软件的投入使用，会面临用户数量增多的情况，用户对软件的使用率也会提升，所以系统面临这种情况，仍然需要通过升级保持性能的合理，这样才能够适应市场；

客户体验：设计出来的程序软件在界面上不能够太复杂，要遵循界面设计的原理设计出简单，方便操作的功能操作界面，让用户易于接受软件，并乐于使用软件提供的功能。
## 4.2 系统结构设计
在系统结构设计上，经综合考虑还是选择比C/S更省资金的B/S结构模式，现如今浏览器已经实现了普及，并在技术上逐渐完善和成熟，它在节约软件开发成本的基础上，还能实现原本用专业软件操作才能实现的强大功能。总之，B/S结构是当下全新的，认可度高的系统构造技术。系统结构设计图通过绘制，效果展示如下：

![](/md/blog.005.png)

图4-1 系统结构设计图
## 4.3功能结构设计
在管理员功能模块确定下来的基础上，对管理员各个功能进行设计，确定管理员功能的详细模块。绘制的管理员功能结构见下图。

在线宠物商城

系个人信息管理

管用户管理

管商品订单管理

管商品收藏管理

大商品管理

修个人信息修改

密

修改密码

新商品新增

是商品修改

删商品删除

删商品收藏删除

申

商品收藏

申

商品收藏修改

删用户删除

新用户新增

修用户修改

用商品订单新增

用商品订单修改 

用商品订单删除 

管宠物管理

新宠物新增

吸宠物修改

删宠物删除
![](/md/blog.006.png)

图4.3 管理员功能结构图

4.4 数据库设计

开发一个系统也需要提前设计数据库。这里的数据库是相关数据的集合，存储在一起的这些数据也是按照一定的组织方式进行的。目前，数据库能够服务于多种应用程序，则是源于它存储方式最佳，具备数据冗余率低的优势。虽然数据库为程序提供信息存储服务，但它与程序之间也可以保持较高的独立性。总而言之，数据库经历了很长一段时间的发展，从最初的不为人知，到现在的人尽皆知，其相关技术也越发成熟，同时也拥有着坚实的理论基础。

4.4.1 数据库概念设计

这部分内容需要借助数据库关系图来完成，也需要使用专门绘制数据库关系图的工具，比如Visio工具就可以设计E-R图（数据库关系图）。设计数据库，也需要按照设计的流程进行，首先还是要根据需求完成实体的确定，分析实体具有的特征，还有对实体间的关联关系进行确定。最后才是使用E-R模型的表示方法，绘制本系统的E-R图。不管是使用亿图软件，还是Visio工具，对于E-R模型的表示符号都一样，通常矩形代表实体，实体间存在的关系用菱形符号表示，实体的属性也就是实体的特征用符号椭圆表示。最后使用直线将矩形，菱形和椭圆等符号连接起来。接下来就开始对本系统的E-R图进行绘制。

（1）下图是用户实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\zaixianchongwushangcheng\用户.jpg](/md/blog.007.jpeg "C:\Users\Administrator\Desktop\img\zaixianchongwushangcheng\用户.jpg")
图4.1 用户实体属性图

（2）下图是宠物实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\zaixianchongwushangcheng\宠物.jpg](/md/blog.008.jpeg "C:\Users\Administrator\Desktop\img\zaixianchongwushangcheng\宠物.jpg")
图4.2 宠物实体属性图

（3）下图是宠物收藏实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\zaixianchongwushangcheng\宠物收藏.jpg](/md/blog.009.jpeg "C:\Users\Administrator\Desktop\img\zaixianchongwushangcheng\宠物收藏.jpg")
图4.3 宠物收藏实体属性图

（4）下图是购物车实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\zaixianchongwushangcheng\购物车.jpg](/md/blog.010.jpeg "C:\Users\Administrator\Desktop\img\zaixianchongwushangcheng\购物车.jpg")
图4.4 购物车实体属性图

（5）下图是论坛实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\zaixianchongwushangcheng\论坛.jpg](/md/blog.011.jpeg "C:\Users\Administrator\Desktop\img\zaixianchongwushangcheng\论坛.jpg")
图4.5 论坛实体属性图

（6）下图是商品实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\zaixianchongwushangcheng\商品.jpg](/md/blog.012.jpeg "C:\Users\Administrator\Desktop\img\zaixianchongwushangcheng\商品.jpg")
图4.6 商品实体属性图

（7）下图是宠物留言实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\zaixianchongwushangcheng\宠物留言.jpg](/md/blog.013.jpeg "C:\Users\Administrator\Desktop\img\zaixianchongwushangcheng\宠物留言.jpg")
图4.7 宠物留言实体属性图

（8）下图是宠物预定订单实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\zaixianchongwushangcheng\宠物预定订单.jpg](/md/blog.014.jpeg "C:\Users\Administrator\Desktop\img\zaixianchongwushangcheng\宠物预定订单.jpg")
图4.8 宠物预定订单实体属性图

（9）下图是商品收藏实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\zaixianchongwushangcheng\商品收藏.jpg](/md/blog.015.jpeg "C:\Users\Administrator\Desktop\img\zaixianchongwushangcheng\商品收藏.jpg")
图4.9 商品收藏实体属性图

（10）下图是商品评价实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\zaixianchongwushangcheng\商品评价.jpg](/md/blog.016.jpeg "C:\Users\Administrator\Desktop\img\zaixianchongwushangcheng\商品评价.jpg")
图4.10 商品评价实体属性图

（11）下图是商品订单实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\zaixianchongwushangcheng\商品订单.jpg](/md/blog.017.jpeg "C:\Users\Administrator\Desktop\img\zaixianchongwushangcheng\商品订单.jpg")
图4.11 商品订单实体属性图

（12）下图是收货地址实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\zaixianchongwushangcheng\收货地址.jpg](/md/blog.018.jpeg "C:\Users\Administrator\Desktop\img\zaixianchongwushangcheng\收货地址.jpg")
图4.12 收货地址实体属性图

### 4.4.2 数据库表结构
在进行这部分设计之前，需要明白和掌握数据类型以及各个数据类型的长度范围等知识，因为在一张具体的数据表中，为了方便理解，这里就举个简单的例子。比如用户信息表，这个表格的字段就是用户这个实体具备的属性，这时就需要对字段进行数据类型，以及字段长度的设置，也要设置一个主键来作为用户信息表的唯一标识。这些都是数据库表结构设计需要完成的内容。根据在线宠物商城的功能设计以及数据库设计要求，展示该系统的数据表结构。

表4.1收货地址表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yonghu\_id|Integer|创建用户|是|
|3|address\_name|String|收货人|是|
|4|address\_phone|String|电话|是|
|5|address\_dizhi|String|地址|是|
|6|isdefault\_types|Integer|是否默认地址|是|
|7|insert\_time|Date|添加时间|是|
|8|update\_time|Date|修改时间|是|
|9|create\_time|Date|创建时间|是|
表4.2购物车表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yonghu\_id|Integer|所属用户|是|
|3|shangpin\_id|Integer|商品|是|
|4|buy\_number|Integer|购买数量|是|
|5|create\_time|Date|添加时间|是|
|6|update\_time|Date|更新时间|是|
|7|insert\_time|Date|创建时间|是|
表4.3宠物表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|chongwu\_name|String|宠物名称|是|
|3|chongwu\_photo|String|宠物照片|是|
|4|chongwu\_video|String|宠物视频|是|
|5|chongwu\_age|String|年龄|是|
|6|chongwu\_types|Integer|省|是|
|7|chongwu\_erji\_types|Integer|市|是|
|8|chongwu\_leixing\_types|Integer|宠物类型|是|
|9|chongwu\_new\_money|BigDecimal|价格|是|
|10|chongwu\_dian\_name|String|线下店名|是|
|11|chongwu\_address|String|线下位置|是|
|12|chongwu\_clicknum|Integer|点击次数|是|
|13|chongwu\_content|String|宠物介绍|是|
|14|shangxia\_types|Integer|是否上架|是|
|15|chongwu\_delete|Integer|逻辑删除|是|
|16|create\_time|Date|创建时间|是|
表4.4宠物收藏表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|chongwu\_id|Integer|宠物|是|
|3|yonghu\_id|Integer|用户|是|
|4|chongwu\_collection\_types|Integer|类型|是|
|5|insert\_time|Date|收藏时间|是|
|6|create\_time|Date|创建时间|是|
表4.5宠物留言表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|chongwu\_id|Integer|宠物|是|
|3|yonghu\_id|Integer|用户|是|
|4|chongwu\_liuyan\_text|String|留言内容|是|
|5|insert\_time|Date|留言时间|是|
|6|reply\_text|String|回复内容|是|
|7|update\_time|Date|回复时间|是|
|8|create\_time|Date|创建时间|是|
表4.6宠物预定订单表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|chongwu\_order\_uuid\_number|String|预约流水号|是|
|3|chongwu\_id|Integer|宠物|是|
|4|yonghu\_id|Integer|用户|是|
|5|insert\_time|Date|申请时间|是|
|6|chongwu\_order\_yesno\_types|Integer|审核状态|是|
|7|chongwu\_order\_yesno\_text|String|审核意见|是|
|8|update\_time|Date|审核时间|是|
|9|create\_time|Date|创建时间|是|
表4.7字典表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|dic\_code|String|字段|是|
|3|dic\_name|String|字段名|是|
|4|code\_index|Integer|编码|是|
|5|index\_name|String|编码名字|是|
|6|super\_id|Integer|父字段id|是|
|7|beizhu|String|备注|是|
|8|create\_time|Date|创建时间|是|
表4.8论坛表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|forum\_name|String|帖子标题|是|
|3|yonghu\_id|Integer|用户|是|
|4|users\_id|Integer|管理员|是|
|5|forum\_content|String|发布内容|是|
|6|super\_ids|Integer|父id|是|
|7|forum\_types|Integer|帖子类型|是|
|8|forum\_state\_types|Integer|帖子状态|是|
|9|insert\_time|Date|发帖时间|是|
|10|update\_time|Date|修改时间|是|
|11|create\_time|Date|创建时间|是|
表4.9商品表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|shangpin\_name|String|商品名称|是|
|3|shangpin\_photo|String|商品照片|是|
|4|shangpin\_types|Integer|商品类型|是|
|5|shangpin\_erji\_types|Integer|二级分类|是|
|6|shangpin\_kucun\_number|Integer|商品库存|是|
|7|shangpin\_price|Integer|购买获得积分|是|
|8|shangpin\_old\_money|BigDecimal|商品原价|是|
|9|shangpin\_new\_money|BigDecimal|现价|是|
|10|shangpin\_clicknum|Integer|点击次数|是|
|11|shangpin\_content|String|商品简介|是|
|12|shangxia\_types|Integer|是否上架|是|
|13|shangpin\_delete|Integer|逻辑删除|是|
|14|create\_time|Date|创建时间|是|
表4.10商品收藏表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|shangpin\_id|Integer|商品|是|
|3|yonghu\_id|Integer|用户|是|
|4|shangpin\_collection\_types|Integer|类型|是|
|5|insert\_time|Date|收藏时间|是|
|6|create\_time|Date|创建时间|是|
表4.11商品评价表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|shangpin\_id|Integer|商品|是|
|3|yonghu\_id|Integer|用户|是|
|4|shangpin\_commentback\_text|String|评价内容|是|
|5|insert\_time|Date|评价时间|是|
|6|reply\_text|String|回复内容|是|
|7|update\_time|Date|回复时间|是|
|8|create\_time|Date|创建时间|是|
表4.12商品订单表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|shangpin\_order\_uuid\_number|String|订单号|是|
|3|address\_id|Integer|收获地址|是|
|4|shangpin\_id|Integer|商品|是|
|5|yonghu\_id|Integer|用户|是|
|6|buy\_number|Integer|购买数量|是|
|7|shangpin\_order\_true\_price|BigDecimal|实付价格|是|
|8|shangpin\_order\_courier\_name|String|快递公司|是|
|9|shangpin\_order\_courier\_number|String|订单快递单号|是|
|10|shangpin\_order\_types|Integer|订单类型|是|
|11|shangpin\_order\_payment\_types|Integer|支付类型|是|
|12|insert\_time|Date|订单创建时间|是|
|13|create\_time|Date|创建时间|是|
表4.13用户表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yonghu\_name|String|用户姓名|是|
|3|yonghu\_phone|String|用户手机号|是|
|4|yonghu\_id\_number|String|用户身份证号|是|
|5|yonghu\_photo|String|用户头像|是|
|6|yonghu\_email|String|电子邮箱|是|
|7|yonghu\_sum\_jifen|BigDecimal|总积分|是|
|8|yonghu\_new\_jifen|BigDecimal|现积分|是|
|9|huiyuandengji\_types|Integer|会员等级|是|
|10|create\_time|Date|创建时间|是|
表4.14管理员表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|username|String|用户名|是|
|3|password|String|密码|是|
|4|role|String|角色|是|
|5|addtime|Date|新增时间|是|




5. # 系统实现
系统实现这个章节的内容主要还是展示系统的功能界面设计效果，在实现系统基本功能，比如修改，比如添加，比如删除等管理功能的同时，也显示出系统各个功能的界面实现效果，该部分内容一方面与前面提到的系统分析，系统设计的内容相呼应，另一方面也是一个实际成果的展示。
## 5.1管理员功能实现
### 5.1.1 宠物管理
此页面让管理员管理宠物的数据，宠物管理页面见下图。此页面主要实现宠物的增加、修改、删除、查看的功能。

![](/md/blog.019.png)

图5-1 宠物管理页面
### 5.1.2 商品信息管理
商品信息管理页面提供的功能操作有：新增商品，修改商品，删除商品操作。下图就是商品信息管理页面。

![](/md/blog.020.png)

图5.3 商品信息管理页面
### 5.1.3宠物类型管理
宠物类型管理页面显示所有宠物类型，在此页面既可以让管理员添加新的宠物信息类型，也能对已有的宠物类型信息执行编辑更新，失效的宠物类型信息也能让管理员快速删除。下图就是宠物类型管理页面。

![](/md/blog.021.png)

图5.4 宠物类型列表页面

第6章 系统测试

程序软件的开发阶段也包括了系统测试，这个部分就是程序质量评定的一个重要环节，如果说程序通过编码实现功能之后，不通过测试检查程序中出现的错误，那么程序一旦投入生活中运行使用时，就会产生许多大大小小的错误，这个时候去解决问题已经晚了，所以一个程序在被交付给使用者使用之前，开发者就需要使用多种测试方法反复进行测试，也是对程序的一个负责表现。程序进入系统测试阶段，在讲究策略进行测试时，也需要对时效性进行把控。当开发者测试完程序，并解决完测试期间程序产生的各种错误时，就需要程序的验收方来对程序进行验收测试，这也是程序测试的最后一个操作步骤。验收测试也是对程序的质量以及可交付性方面起到关键的作用。











