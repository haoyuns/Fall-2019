### Week 4-5

<details>
  <summary>展开</summary>
  
  #### 色彩基础
  - **原色、间色、复色**
    - 原色 Primary Colors  
    指不能透过其他颜色混合调配而得出的“基本色”，三原色“红、黄、蓝”
    - 间色/二次色 Secondary Colors  
    由两种等量的原色混合而成，如橙=红+黄、紫=红+蓝、绿=蓝+黄
    - 复色/第三色 Tertiary Colors  
    由色轮上的间色与其相邻的原色混合而成，如黄橙色、蓝紫色
    - 互补色 Complementary Colors  
    色轮上二次色与其正对面的原色为互补色，如红色与绿色、蓝色与橙色
  
  - **色彩三属性**：色相、饱和度、明度
    - 色相 Hue  
    简单来说，就是色轮上的12种颜色，如红色，黄色
    - 饱和度/色度 Saturation  
    指某个颜色的强度，数值越高色彩越纯，低则逐渐变灰
    - 明度/亮度 Value  
    指颜色的亮度：往一个颜色里加白色，明度就提高；反之加黑色，明度降低。两个极端就是黑、白两色
    
  - **RGB** vs **CMYK**
    - RGB [三原色光模式][rgb]：**适用于电子屏幕**，三种颜色的光聚在一起形成白光，缺乏光（屏幕关闭）即是黑色  
    ![rgb](images/rgb.jpg)
    
    - CMYK [印刷四分色模式][cmyk]：青色 Cyan、品红 Magenta、黄色 Yellow、黑色 Key，**适用于印刷品**  
    由于现实情况中，前三种颜色的油墨叠印而成的并不是纯黑，所以需要专门定位标准的黑色，称为Key。没有油墨即是白色  
    ![cmyk](images/cmyk.png)
  
  [rgb]: https://zh.wikipedia.org/wiki/%E4%B8%89%E5%8E%9F%E8%89%B2%E5%85%89%E6%A8%A1%E5%BC%8F "RGB mode"
  [cmyk]: https://zh.wikipedia.org/wiki/%E5%8D%B0%E5%88%B7%E5%9B%9B%E5%88%86%E8%89%B2%E6%A8%A1%E5%BC%8F "CMYK mode"
  
  #### 色彩搭配思路
  - **单色** Monochromatic
  <img src="images/c-mono.jpeg" width="400">
  
  - **类似** Analogous  
  色轮上彼此相邻的颜色组成
  <img src="images/c-analogous.jpeg" width="400">
  
  - **互补** Complementary  
  色轮中完全对立的颜色为互补色
  <img src="images/c-complementary.jpeg" width="400">
  
  - **等边互补** Split Complementary  
  选择一种颜色，再在色轮上找出它正对面的互补色；  
  不直接使用这个互补色，而是使用该互补色两侧的颜色
  <img src="images/c-split.jpeg" width="400">
  
  #### 基于数据的色彩选择
  - **离散型**色系 Diverging  
  两端颜色为互补色（如红色与绿色），中段颜色通常较浅；可以强调中间值域，并且使得两端的数据一目了然，适合偏重极值和中间值的数据  
  ![离散](images/d-diverging.png)
  
  - **序列型**色系 Sequential  
  一般是同一色调（Hue）的由浅及深或由深至浅；数值较小用浅色，较大用深色，适合单一主题、比重比较平均的数  
  ![序列](images/d-sequential.png)
  
  - **分类型**色系 Qualitative/Categorical  
  分类型的每种颜色都“各不相关”，采用不同色调；适合用来区分不同种类下的数据，如区分土地用途
  ![分类](images/d-qualitative.png)
  
  - **ColorBrewer** [演示][http://colorbrewer2.org/#type=sequential&scheme=BuGn&n=3]
  
</details>

### Week 3

<details>
  <summary>展开</summary>
    
#### 又是 Markdown
- Markdown 诞生于2004年，由 John Gruber（在 Aaron Swartz 协助下） 创造
  - 题外话：关于 Aaron Swartz 的纪录片，[互联网之子](https://movie.douban.com/subject/25785114/ "The Internet's Own Boy")
- 如何插入图片？如何空一行？空格有意义吗？…… 简明教程：[指令](https://commonmark.org/help/)，交互式教程（必看！）在[这里](https://commonmark.org/help/tutorial/)，可在[这个网站](https://daringfireball.net/projects/markdown/dingus)练习
- GitHub 风味的 Markdown [说明](https://github.github.com/gfm/)
  
#### 多看多读多听
- **讲者**
  - Giorgia Lupi, [How we can find ourselves in data](https://www.ted.com/talks/giorgia_lupi_how_we_can_find_ourselves_in_data "TED: How we can find ourselves in data")
  - How to [Build a Connection With Your Data Through Original Visualization](https://dataviztoday.com/shownotes/28 "Dataviz Today: How to Build a Connection With Your Data Through Original Visualization")

- **有关“量化”**
  - 你是“量化青年”吗？[1](http://www.qdaily.com/articles/31671.html "好奇心日报"), [2](http://notch.qdaily.com/mobile/posts/4878.html)
  - 不得不[被量化的运动员](http://www.qdaily.com/articles/38283.html)

- **不一样的信息来源**
  - [「后续」App](https://www.weibo.com/p/1005056581210531 "「后续」微博")
  - 好奇怪 App, [好奇心日报](http://www.qdaily.com/articles/64091.html)
  - 端传媒 [Initium Media](https://theinitium.com/)
  - [Matters 社区](https://matters.news/)

- **可视化案例**
  - [The Pudding](https://pudding.cool/)
  - *The Economist*, [Graphic Detail](https://www.economist.com/graphic-detail/)
  - FlowingData <http:www.flowingdata.com>
  - Reddit 话题 [dataisbeautiful](https://www.reddit.com/r/dataisbeautiful/)
  - Data Visualization Society, [资源](https://www.datavisualizationsociety.com/ "Data Visualization Society"), [文章](https://medium.com/nightingale "Medium articles")
  
  - **音乐**
    * Doodle Chaos [Youtube 主页](https://www.youtube.com/user/DoodleChaos/videos "Doodle Chaos")
    * Nicholas Rougeux [Youtube 主页](https://www.youtube.com/channel/UCRQH9-hWxELNCv47z2O5nfg), 作品之一[卡农](https://www.youtube.com/watch?v=DxkpN4PUOzA)
    * Giant Steps [爵士名曲“巨人脚步”可视化](https://www.youtube.com/watch?v=rh6WTAHKYTc&list=WL&index=4&t=0s)
    
  - **情感**
    * Louise Ma, [What Love Looks Like](https://vimeo.com/70813009 "What love looks like"), [See by Touch](https://love.seebytouch.com/archive/filter-by/photo/tagged/love "Louise Ma, seebytouch.com")
    * Lam Thuy Vo, [Quantified Breakup](https://quantifiedbreakup.tumblr.com/page/2 "Quantified Breakup") 
    * Nicholas Felton, 个人数据可视化“鼻祖” annual [personal reports 2005-2014](http://feltron.com/index.html)

- **数据集**
  - Data is Plural [邮件订阅](https://tinyletter.com/data-is-plural/archive)
  - Kaggle [数据集](https://www.kaggle.com/datasets)
  - Reddit Data Challenge
  
- **数据新闻[公开课](https://journalismcourses.org/DATA0819.html)**  
Data Journalism and Visualization with Free Tools (10.14 - 11.24)

**作业（`10月17日中午前`提交）**
1. 用不同的可视化工具呈现同一个数据集

- 调研目前免费的可视化图表工具（国内外都得有，在线离线、交互静态都行）
- 在 [Kaggle](https://www.kaggle.com/datasets) 选择一个公开数据集（可以只截取部分数据）
- 用你调研的图表工具（不少于3种）呈现上面选取的数据
- 在 markdown 里列出所选数据集、使用的工具及呈现，并附上使用体会
  
2. 之前提交不规范，或还没掌握 markdown 基础的同学，修改已提交作业的 markdown 文档
3. **按个人需求和计划**，消化本周所列的链接内容，并注册[公开课](https://journalismcourses.org/DATA0819.html)学习

</details>

### Week 2

<details>
  <summary>展开</summary>

#### 数据的类型
- 定类/名义（nominal/categorical/set of characters）：描述特征，不具有数值意义。如名字、性别、民族、车辆品牌、地点
- 定序（ordinal/sequence）：分类和排序都有意义。如教育水平、问卷中的偏好程度等
- 定距（interval）：没有绝对0点，数值间距相等，互相可以加减，但乘法无意义。如摄氏度、IQ
- 定比（ratio）：有绝对0点（true/meaningful zero point），一个值是另一个值的倍数或比率，可计算差、中位数、均值等。如质量、高度、速度
- 离散（discrete）：整数
- 连续（continuous）：小数点位数没有限制

#### 数据录入（课堂练习1）
- “列”对应变量，“行”对应信息录入（columns for variables & rows for observations）
- 每一格应该只对应单一信息
- 命名时避免数值、空格和特殊字符，数值单位需指明
- “0”和“空白”的差异（0是数值，空白是null）
  ![ways to input null data](images/null.png)
- 数据核验
- 输出时应导出为csv等通用格式
- 输出时应附上元数据（metadata: data about data）

#### The Eyeball Test（课堂练习2）
- 提问：5W & H
- command+箭头
- 每一列记录的是什么信息？数据单位是什么？数据类型是什么？
- 每份数据应该有一个说明和元数据，找出数据背后的上下文
- 字符是英文还是中文，输入时有空格吗，有空白数据吗
- 练习2：2017年蔬菜产量最高的10个国家是？（数据：[联合国粮农组织](http://www.fao.org/faostat/zh/?#data)）

#### 数据处理
- csv导入，文档编码与乱码 (tsv, fixed width)
- 冻结首排，开启过滤功能
- 排序(sorting)
- 过滤(filtering)
- 公式([functions][阅读5])
  - sum(), average(), median()
  - upper(), lower(), proper()
  - concatenate(), trim()
  - left(), right()
- 数据透视表（pivot tables）
- Excel bugs：[行数](https://blog.csdn.net/zhongguomao/article/details/77737800),[日期](https://www.cnblogs.com/guogangj/p/9419453.html)

#### Tips
- 保存、保存、保存
- 记录每一步操作
- 数据备份，不更改原始数据（raw data）
- 如果已经有了机构的分析，依然要做完你自己的分析来核实
- 了解你的数据后再动手
- 和同仁交叉核对
- 如果条件允许，去实地调查数据是如何被收集及记录的

**作业（`10月9日前`提交）**
1. 搜索并阅读《上海市公共数据开放暂行办法》
2. 搜索并回答：我国还有哪些关于公共数据开放的条例或法规？国内外有哪些政府开放数据平台？（markdown文档，列出信源和链接，包括👆🏻上海这个）
3. 在国家统计局[数据库](http://data.stats.gov.cn/index.htm)找到全国GDP数据，回答：2012-2018年各季度GDP增速（列出选取的统计指标、数据页面、计算步骤及答案）
4. 阅读👇🏻

**阅读**
1. 高敏雪，[《什么是政府统计》](https://cosx.org/2019/08/what-is-gov-stats/)
2. 任怡萌，[《电子表格中的数据整理》](https://cosx.org/2018/07/data-organization-in-spreadsheets/)
3. Hadley Wickham, [_Tidy Data_](https://www.jstatsoft.org/article/view/v059i10)
4. Ethan P. White, [_Nine simple ways to make it easier to (re)use your data_](https://peerj.com/preprints/7/)
5. Microsoft, [_Top ten ways to clean your data_](https://support.office.com/en-us/article/Top-ten-ways-to-clean-your-data-2844b620-677c-47a7-ac3e-c2e157d1db19)

[阅读5]: https://support.office.com/en-us/article/Top-ten-ways-to-clean-your-data-2844b620-677c-47a7-ac3e-c2e157d1db19 "Top ten ways to clean your data"

</details>

### Week 1

<details>
  <summary>展开</summary>
  
#### 对数据的“背景调查”：Who, What, When, Where, Why, How?
- 不管发布机构有多权威，数据都是可质疑的
- 人工会不同程度地参与数据整合过程，难免偏差与错误：To err is human.
- 永远检查数据集的元数据（Metadata）

#### 个人数据的价值：[Dear Data](https://www.dear-data.com/theproject "Dear Data")

#### GitHub 及 Markdown
- GitHub Pages 主题选择：[https://pages.github.com/themes/](https://pages.github.com/themes/)
- Markdown Cheatsheet：[https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- Markdown 教程：[https://www.markdowntutorial.com/](https://www.markdowntutorial.com/)

**作业（`9月30日前`提交）**
1. 收集某个主题的个人数据，不限时间，规整为数据集
2. 参考 Dear Data 的表现方式，拓展想象力
3. 以手绘的形式呈现第一步收集的数据（无所谓美感，能展现想法为主），纸张大小 ≥ 明信片
4. 以 markdown 文档形式记录自己的上述过程操作或感想
5. 在同一个 markdown 文档里回答：你认为日常生活中哪些数据是被搜集的？被谁搜集了？

</details>
 
#### 课程目标
- 锻炼信息获取、辨别及核实的能力
- 锻炼数据处理及分析的能力
- 基本设计概念与图表制作
- 教学相长

#### 软件准备
- Excel, Ai, R, Sublime Text

#### 参考阅读
- [Data Journalism Handbook](https://datajournalism.com/read/handbook/two "Data Journalism Handbook")
- [R Graphics Cookbook](https://r-graphics.org/ "R Graphics Cookbook"), 2nd edition
- [Data + Design](http://orm-atlas2-prod.s3.amazonaws.com/pdf/13a07b19e01a397d8855c0463d52f454.pdf "Data + Design")

#### 评分
- 平时作业 60%
- 期末项目 30%
- 课堂参与 10%

平时作业包含软件操作、信息搜集、数据申请或数据分析等。期末项目要求在与老师讨论后，独立完成一个以采访为基础、数据驱动、包含信息设计与呈现的作品。

#### 加分项
- 数据获取难度高
- 数据处理和分析有明晰记录
- 视觉美感

#### 扣分或直接不及格项
- 援引内容不注明信源或链接
- 使用二手数据，未经核实的数据
- 信息获取方式不合伦理（如采访时没公开记者身份等）
- 编造信息或内容
- 大段改写或抄袭（包括设计抄袭）
- 缺勤6次以上

#### 隐私
- 课堂上的拍照、录音和录像仅供个人学习使用，未经当事人书面允许请勿任意传播
- 互相尊重，不合适言行当面指出
