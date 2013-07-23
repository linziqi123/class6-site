Class6
======

The website of Class6 

网站具体需求分析

网站具体模块包括：

　　1首页、2功课资料、3技术潮六、4图坝、5留言、6生日快报、7通讯录、8相约恩师。  共8个模块。

下面具体介绍下各个模块要完成什么：

　　1 、首页。

　　首页像一般的网站，需要展示各个重要模块的部分动态信息，包括 最新上传的功课资料、技术潮六论坛的动态、图坝的动态、留言的动态、生日快报的动态、通讯录暂时不在首页中展示（因为暂时不需要太多更新），还有相约恩师，可以在首页上给一个区域展示我们的恩师以及相约恩师模块上的动态。

　　显示动态，让访问者最先看到最新的信息，除了这些，首页还包括 登录和注册 模块，内容搜索 模块。其中内容搜索需要仔细考虑下，如何使用 Ajax 来实现搜索功能，这些前台er 要考虑多一点。

　　另外，首页的风格将决定网站的主体风格，所以在设计前要做好构思，在设计中要注意用户体验。

　　2 、功课资料

       功课资料这个模块包括的功能：上传功课资料（初期为特定管理员来完成）、下载功课资料、（可增设预览功课资料） 。暂时完成这些，后期有需要的话可以更新。

　　注：其中上传功课资料需要包括 资料标题、上传人、上传日期、资料有效期、备注等相关信息，具体在设计中考虑。

　　3、技术潮六

       这是一个大块，它是一个小论坛，注意功能是交流和讨论一个技术知识。具体功能包括：
 
      （1）发帖（发帖人有删除帖的权限，不能修改帖内容）

      （2）查看论坛相应类别的帖

      （3）回复贴（即评论）（回复要先登录）

      （4）管理员删除和修改贴

　　论坛设计中可以参考下其他论坛的设计，比如说红满堂、CSDN论坛 .. 

　　由于论坛发帖量会增加，这里帖展示区的设计中，要考虑内容的可扩展性，即但帖子数过多时，要如何来显示所有的帖，如何来设计分页。还有，上面提到的相应类别，即技术帖需要分类，比如说 网页设计帖、C语言帖、安卓开发帖 什么什么的，这个页面相应人员在设计中要考虑下，给论坛初始化几个分类。分类同样要考虑可扩展性，即分类增多时怎么办？

　　4 、图坝

　　图坝类似于 QQ 空间的相册，用来储存和展示班级相关的图片。其中包括如下功能：

　　上传图片

　　由于班级网站的权限是所有童鞋， 只要登录即可上传图片，这一点不像空间的个人相册。我们这里的上传图片，其他登录童鞋都可以看到，可以知道是谁什么时候上传的图片，即是图片分享。

　　新建相集

　　图坝设计中将会初始化几个相集，你要上传图片，可以选择上传到已有的相集，也可以新建相集，来存放你要上传的图片。所以这里在设计中同样要考虑可扩展性，当相集增多了，页面要怎么办？

　　删除相集

　　所有童鞋有权限新建相集，并为它命名。当然，相集也可以删除，不过只有相集的新建主人和管理员才可以删除。删除相集后，相集里所有相片都会删除，所以这里要设计删除确认提示，以防误删。

　　删除相集中的相片

　　相集中的相片可以单张删除，也将支持多张批量删除。

　　评论相片

       登录者可以评论相片。其他人可以对评论进行回复。
　　评论者暂时不可以删除评论，管理员可以删除评论。

　　注：图片重在展示，所以在图坝页面的设计中，要注意如何来展示相集，如何来展示相片，才能达到更好的用户体验，这一点要考虑考虑。

　　5 、留言

　　留言区，也是一个很好的交流平台，登录者可以在这里留言，其他人可以查看留言并发表评论。留言者暂时木有删除留言的功能，包括自己的留言，只有管理员可以删除留言。

　　当然，留言这里同样需要考虑可扩展性，如何利用分页来存放所以留言。

　　6 、生日快报

　　生日快报，即是管理我们班级童鞋的生日，以及通知和提醒临近的生日。具体功能可以有：

　　（1）查看所有童鞋的生日（哇！这里有些童鞋可能会觉得侵犯偶滴隐私权，对不起罗）
　　（2）生日提醒。即将生日或生日刚过不久的童鞋，在页面上要做提醒。如何提醒，那要看你怎么设计了。这里可以编写固定样式，然后通过后台来动态查找和显示最新生日。
　　（3）发表生日祝福。登录者可以在查看生日提醒后发表生日祝福，类似于留言中的回复功能。
　　（4）历史生日列表。

　　因为每一个生日，都有不一样的祝福，所以这里我们要把这些生日和祝福保存下来，类似于留言板中的留言。用户可以查看历史生日，查看其祝福，但这里暂时不支持为历史生日发表祝福。（过去就让它过去了）

　　7 、通讯录

　　这个是为了方便童鞋查找班级通讯录而设计的，其中暂时不需要动态功能，只写静态显示页面，所以有一个要求，风格要设计漂亮点。

　　8 、相约恩师

　　这个模块也很重要。我们发现，上大学后我们与老师的交流变少了，为了与恩师做更多的交流，我们增加了这个模块。网站建成后，我们将邀请恩师注册我们的网站，与我们一起交流。模块将包括以下功能：

　　恩师简介

　　这里将由设计人员收集各个老师的资料（包括联系方式），然后做展示，让童鞋们更了解我们的老师。

　　对恩师的评价

　　登录的童鞋可以对老师做中肯的评价，类似于留言板中的评论，可以给老师打分。

　　恩师和其他登录者可以对评价进行回复，不过这里要区别下恩师和童鞋。

　　管理员可以删除评价（不中肯的评价 ..）

　　8+1 、登录和注册模块

　　这里有一点要注意下，因为上面提到，发布者有些特别权限，比如说可以删除自己建立的相集，恩师和童鞋的评论有区别效果，所以我们在设计注册这块，一要给每个童鞋一个特定的标签（比如id），二要给老师一个不同的标签。

　　----------------------

　　Ok！以上是对六班网站各个模块的具体需求分析，我们接下来的设计将按照这个方案来进行。

　　计划：先开始前台页面的设计，期间 后台继续积累知识，慢慢实现各项功能。

　　注：由于我们后台涉及到的功能实现有些难度，需要完整的知识体系才能设计成功，比如说数据库的建立，所以后台的设计时间跨度会稍长。当然，页面也要努力。

　　2013/7/23

