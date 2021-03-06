## PS安装和破解

破解时主要使用 **Adobe Zii**

[PS CC2018破解参考地址](http://www.gfxcamp.com/photoshop-cc-2018/)

[MAC 版破解工具](https://www.luongovincenzo.it/blog/adobe-mac-adobe-cc-2015-2019-crack-activation-all-in-one-patcher-adobe-zii-mac-osx/)

## Day01 基础及选框工具
2018-02-24
### 1、PS界面中复位基本功能
窗口--工作区--复位基本功能

### 2、基本操作

注意：新建画布之后必须先另存为 psd 文件，然后才能进行相关操作

MAC快捷键|Win快捷键|功能
---|---|---
CMD + N |ctrl+N|新建画板
shift+cmd+s |ctrl+shift+s|另存为
.|ctrl+o|打开文件
。|alt+del|填充前景色到选择区域
.|ctrl+del|填充背景色到选择区域
cmd+z|ctrl+z|后退，单步后退
alt+cmd+z|ctrl+alt+z|后退，最多可退20步
.|ctrl+shift+alt+N|新建图层
。|ctrl+t|自由调整素材大小（**调整时按住 shift 可以等比缩放**）
。|ctrl+d|取消选框
。|按住alt+鼠标滚轮|缩放工作区
。|按住空格，然后按下并移动鼠标左键进行平移|平移工作区（工作区超过屏幕范围时可用）
。|shift+矩形区域选择工具|绘制正方形选区
。|ctrl+e|合并图层
.|按下alt,然后拖动图层中的对象|复制图层对象

### 3、图层的理解
将不同的组成部分进行分解，便于编辑。

**建立图层需要在做出具体操作之前进行。**

### 4、电视机界面的创建

* 新建空白画布，并且另存为 PSD文件
* 打开提前准备的电视机界面素材.jpg 文件
* 使用 移动工具（V）拖拽打开的 电视机素材图层 到 之前建好的空白画布中
* 按下 ctrl+T 自由调整 电视机素材图层 的大小，并再次利用 移动工具 移动其位置
* 新建图层，在该图层中 电视机图像区域下方 利用 矩形选框工具  选择2块区域，并为该区域填充颜色
* 新建图层，在 电视机图像 外圈选择一个矩形区域作为电视机边框，并填充颜色
* 调整图层顺序，让 电视机图像 图层显示在顶层
* 选择 移动工具（V），在 属性 栏中选择  居中对齐，将多个图层中的内容进行对齐

效果图示如下：
![](https://gitee.com/uploads/images/2018/0224/212854_ea74e265_930142.png "屏幕截图.png")

### 5、双11宣传图的创建

* ctrl+n 新建空白画板，另存为 psd 文件
* 设置前景色为 红色，背景色为白色，alt+del 填充画板颜色为红色
* ctrl+shift+alt+n 新建图层，假设名图层名为  图层1 
* 按下shift键使用矩形选框工具创建正方形选框，ctrl+del 填充选区为白色
* ctrl+d 完成选框
* 按下 alt ，然后使用 移动工具 拖动新建的正方形选框，实现图层复制（拖动时需要调整新图层的位置），假设为图层2 
* 单击右下方图层列表中的 图层1 ，再次按照上一步多次复制图层。
* 在 右下方图层列表中选中图层2 ，然后按住shift键，再选中最后复制出来的图层，实现多图层的选中
* 选中 移动工具，并选中其属性栏中的 按顶分布（多个垂直排列的对象之间的间距相同）
* ctrl+e ,合并图层2 与 后面复制出来的图层（在前面已经将这些图层同时选中了）
* 之后的步骤大致类似，无非就是选中图层1 ，按下alt + 移动工具 实现图层复制，然后合并图层
 

![](https://gitee.com/uploads/images/2018/0224/215857_447de4c3_930142.png "屏幕截图.png")

## Day02 图像合成与渐变
2018-02-24

### 1、套索


### 2、魔棒
* 属性栏 中的 **容差** 可以改变选择范围
* 属性栏 中的 **连续** 表示取样的颜色时相连的还是隔开的，隔开的话，不相连的区域也可以被选中

MAC快捷键|Win快捷键|功能
---|---|---
。 |shift+ctrl+I|反向（即反向选择，所有选框都可用）


在魔棒工具![](https://gitee.com/uploads/images/2018/0224/232337_4be26c64_930142.png "屏幕截图.png")右下角有一个三角，点击之后里面还会有一个 **快速选择** 工具，两者的快捷键都被标识为 **W**。如果需要在 **魔术棒** 、**快速选择** 之间切换的话，可以 **先 按下 shift，然后再按 W** 。其他带有小三角的功能切换时与此同理

### 3、选框修改 V12

* **在使用 快速选择工具 时， 配合 左右中括号按键——【 、 】可以快速的缩放画笔的大小。** 

* 使用 快速选择工具 或者 魔术棒 等方式抠图的时候，边界可能会有白边（或者其他颜色的边框），可以通过 **选择--修改--收缩--1 像素** 来去掉白边（像素值可以自己定义）。 

名称|含义
--|--
选择--修改--收缩|将选区向内缩小
选择--修改--扩展|将选区向外扩大
选择--修改--平滑|为选区制作圆角效果
选择--修改--羽化|使选区边缘具有模糊效果（绘制完选区之后，先羽化再填充或者抠图）。快捷键 **Shift+F6**(MAC 和 win 相同)
选择--修改--边界|做出边框效果

**注意：以上所列的几种修改工具在使用时，不能设置较大的像素值，否则得到的会是多边形**

### 4、选择工具补充
* **单行选框工具**

将画布放大以后，能看到画布的本质是有一个个的像素点组成的，每个像素点的范围时 1X1 像素。所以，单行选框工具就是指 选中一整行的像素点

* **单列选框工具**

单列选框工具就是选中一列像素点。

### 5、渐变工具（shift+G）
渐变：两种或两种以上颜色的渐次变化

#### （1）、渐变工具的基本使用
* 在使用渐变工具时，如果想在画布上展示，需要自己手动在界面上画线，**线越长，颜色之间过渡的越平缓，线越短，颜色直接的过渡色越尖锐（线特别短的话可能就是两种颜色的排列了）**。

* **线的起点和终点的方向（角度）也决定了颜色渐变的方向**

平缓的过度：
![](https://gitee.com/uploads/images/2018/0226/091224_83a509fb_930142.png "屏幕截图.png")

尖锐的过度：
![](https://gitee.com/uploads/images/2018/0226/091504_4f590965_930142.png "屏幕截图.png")

#### （2）、渐变工具的属性栏（渐变编辑器和渐变类型）：

![输入图片说明](https://gitee.com/uploads/images/2018/0226/092030_e345c4b2_930142.png "屏幕截图.png")

渐变类型（线性渐变和径向渐变用的比较多）：

![输入图片说明](https://gitee.com/uploads/images/2018/0226/092126_fd9c647e_930142.png "屏幕截图.png")

#### (3)、渐变编辑器

* 如下图所示：点击 左上角的颜色区域，可以打开渐变编辑器。

![](https://gitee.com/uploads/images/2018/0226/093924_ec5c2e98_930142.png "屏幕截图.png")


* **渐变编辑器用来编辑渐变的颜色类型，以及渐变范围**。 详细如下：
![输入图片说明](https://gitee.com/uploads/images/2018/0226/111117_3fa9519c_930142.png "屏幕截图.png")

#### (4)、用 径向渐变 + 反向 画球

在 使用 **径向渐变** 时，注意与 属性栏中 **反向** 的配合。下面就是二者配合的实例，具体步骤如下：

* 新建图层
* 设置前景色为黑色，背景色为白色
* 选择 **椭圆选框工具（M）**，按下 shift 键，然后在画布中绘制出正圆图形
* 选择 **渐变工具（G）**，点击颜色条右侧的 向下箭头![输入图片说明](https://gitee.com/uploads/images/2018/0226/095219_583afe0a_930142.png "屏幕截图.png")，选择 **前景色到背景色渐变**（默认就是这一个，如果之前没有更改成其他，则不用选择）。渐变类型选择 **径向渐变**，并勾选属性栏中的 **反向**
* 在绘制好的正圆中，从左上角向右下角绘制直线,然后按下 Ctrl+D(MAC下是 CMD+D)取消选区，绘制完成。 

![](https://gitee.com/uploads/images/2018/0226/094438_404710af_930142.png "屏幕截图.png")

#### （5）、为球增加影子
* 前景色置为黑色，并新建画布
* 选择 **渐变工具**--**前景色到透明渐变**，选择 **径向渐变**，并取消 **反向**
* 在画布上直接画线，做出一个中间颜色重，边缘颜色浅的渐变圆形——即阴影图。（注意，此处不需要绘制选框，直接绘制渐变颜色就行）
* 利用 Ctrl+T(MAC 为 CMD+T)自由调整该图形，调整为椭圆（**此时右击，可以切换调整模式，除自由变换外，还有缩放、旋转等模式**）
* 利用 移动工具（V），根据光影效果，动态调整阴影的位置

最终效果如下：
（注意，下图中在按照 （4）中的描述绘制圆球时，先添加了浅绿色的背景色。添加背景色是为了更好的展示阴影效果)

![](https://gitee.com/uploads/images/2018/0226/115124_8adfd9d8_930142.png "屏幕截图.png")



## Day03 钢笔抠图和商业案例 
20180226

### 1、路径 和 选框 的对比
路径也是抠图工具的一种，和选框类似。

* 路径比选框工具更加灵活，可以选出任意形状的区域。
* 路径不能直接对位图进行编辑（比如选中一块区域直接直接删除），但选框工具可以
* **路径与选框的转换：Ctrl+回车**

>在PS CC 中二者的转换和操作有疑问。貌似转换之后也不能直接删除。

### 2、路径的组成

路径包括：**锚点、路径线、手柄控制点、手柄线**。具体如下图：

![](https://gitee.com/uploads/images/2018/0226/211335_cffd824e_930142.png "屏幕截图.png")

先用 **路径工具（U）** 绘制选区，然后选择 **直接选择工具(A)** 即可展示出路径的详细信息。如果选择 **路径选择工具** 的话，会展示出实心锚点，手柄控制点，不可调整路径。

**注意：矩形等直角或锐角图形无手柄**

### 3、钢笔工具（P）
钢笔工具用来描绘形状。具体分为两种：
* 凭空绘制（基于美术功底手工绘制）
* 沿对象描绘（描摹，基于现有素材抠图）

所有的形状都是由直线和曲线组成，所以钢笔工具重点掌握直线绘制和曲线绘制。

#### （1）、钢笔工具绘制直线：
步骤如下：
* 钢笔工具（P）-- 路径
* 在画板上单击增加路径点
* 将光标放置到起始路径点时，如果小钢笔光标右下角展示一个小圆圈，表示要闭合路径 。

具体操作如下图：
![](https://gitee.com/uploads/images/2018/0226/222350_ae739991_930142.gif "2.gif")

在上面的GIF动图中：
* 小钢笔光标右下角为 **星号** * 时，表示新增路径点
* 小钢笔光标右下角为 **圆圈 。** 时，表示闭合路径
* 小钢笔光标右下角为 **加号 +** 时，表示在当前已有路径中增加路径点。（将光标放置到已有的路径上时会有这种情况）
* 小钢笔光标右下角为 **减号 -** 时，表示删除已有路径点。（将光标放置到已有的路径点时，会有这种情况）

#### （2）、钢笔工具绘制曲线：
具体步骤如下：
* 钢笔工具（P）-- 路径
* 单击画布绘制起始锚点
* 单击左键并按住不松并拖拽绘制第二个锚点和链接两个锚点的曲线。（此时该锚点为实心并会展示手柄线）
* 按住 alt 键，并单击第二个锚点，去除一半的手柄线。
* 按照第三步和第四步重复绘制锚点
* 闭合区域

**注意以下内容：**

* 按住alt键之后，**将光标放置到锚点上，直到光标右下角展示一个 < 形状**，此时单击锚点即可删除一半手柄线
* 删除一半控制线是因为不去掉的话会影响下一个锚点的绘制。**不去掉的话，绘制出来的下一个曲线锚点路径可能是一个S形状**；当然了，如果我们需要的就是S形状，则可以不去掉这一半控制线

### 4、钢笔抠图技巧 
（1）钢笔定点要在对象边缘内的 1-2 像素（防止出现边缘不必要的内容）

（2）钢笔拖动方向沿着弧度线相切的方向拖动

（3）抠图中间出现错误时，使用 ctrl+alt+z 多次回退，不能使用 del 删除

（4）抠图时需要放大

（5）抠图完成时使用 ctrl+enter 将路径变为选区

（6）抠图时一定要选择 钢笔工具--路径

（7）锚点之间的间距不要定的太长，太长的话手柄也长，导致弧度不好控制

### 5、标尺和扩大画布
MAC下快捷键|win下快捷键|含义
--|--|--
CMD+R|Ctrl+R |显示标尺，辅助做图，比如对齐、找有效区域等
与win操作相同 |从标尺的刻度上向下拖拽（如果是左侧标尺则向右拖拽）|调出辅助线，辅助线的作用类似于标尺
。|ctrl+j|拷贝图层或者选框中的对象
cmd+A|ctrl+A |全选，制作整个页面的选框
cmd+；|ctrl+;|显示或隐藏辅助线（如果已有辅助线但被隐藏了可显示，如果辅助线正在显示则隐藏）

#### (1)、利用标尺和自由变换工具确定画布中间线
具体步骤如下：
* 新建画布，并另存为本地psd文件
* cmd+r （win 下用 ctrl+R ）调出标尺
* 将光标放置到上方标尺刻度上，光标变成箭头时向下拖拽，绘制水平辅助线
* 将光标放置到左方标尺刻度上，光标编程箭头时向右拖拽，绘制垂直辅助线
* 为画布填充颜色或其他内容（**如果不填充，在使用 自由变换工具 时会提示：无法变换所选像素，因为所选区域为空**）
* cmd+a (win下为 ctrl+a)全选当前页面内容
* cmd+t (win下为 ctrl+t)调出自由变换工具，此时，画布边界上会展示四个中心点
* 基于自由变换工具展示的中心点绘制中心辅助线（辅助线的绘制参考第三和第四步）
* 绘制完成之后点击回车取消自由变换状态。

整个步骤也可参考下面的动图：
![](https://gitee.com/uploads/images/2018/0227/092956_723f579f_930142.gif "02.gif")

#### (2)、扩大画布
MAC快捷键|Win快捷键|作用
--|--|--
alt+cmd+c|.|调整画布大小
![](https://gitee.com/uploads/images/2018/0227/095620_8ea53112_930142.png "屏幕截图.png")

### 6、存储路径和隐藏路径

#### （1）、隐藏路径
打开一个已经存储过路径的素材时，默认会展示已经保存的路径，为了避免干扰，**在右下角路径面板中点击空白处**即可隐藏路径

#### （2）、存储路径
步骤如下：
* 利用钢笔工具绘制路径
* 右下角路径面板中会显示 **工作路径**，表示正在绘制的路径，这是一个临时的
* **双击路径面板中的 工作路径**，弹出路径保存面板，命名并保存即可。**保存之后，默认选中该路径，如果需要新建路径，需要点击空白处隐藏该路径**
* 最后，将该图保存为 psd 或者 jpg 文件，即可将路径与文件一起保存。（**推荐存储为jpg,因为它只能存储路径；而psd除了路径还会保存图层**）

#### （3）、存储路径和隐藏路径的GIF示意如下：
![](https://gitee.com/uploads/images/2018/0227/101432_19458e5a_930142.gif "02-line.gif")

### 7、耐克 banner 案例 V21
#### （1）、文字工具（T）

* 文字工具的属性栏
![](https://gitee.com/uploads/images/2018/0227/102309_13267dc4_930142.png "屏幕截图.png")

* 文字工具的类型

如下图：前两种是普通的横排和竖排文字工具，比较常用；后两种是带有选取的文字工具，不常用
![](https://gitee.com/uploads/images/2018/0228/080343_d0fbf537_930142.png "屏幕截图.png")

#### （2）、文字工具的基本使用步骤
* 选择 **文字工具（T）**
* 在画布上单击并输入内容，
* 输入完成后使用属性栏中的 提交工具![](https://gitee.com/uploads/images/2018/0228/080218_5e58a17d_930142.png "屏幕截图.png")进行提交 
* 如果输入错误，可以按下工具栏中的 取消工具 ![](https://gitee.com/uploads/images/2018/0228/080815_ba35b544_930142.png "屏幕截图.png")，清除单个文本框和内容

#### (3)、文字工具的其他使用技巧

##### A 、全选文字
在右下方图层面板中，**双击**下图中 **红圈圈中的地方** 可以 **全选该文本框中的文字**
![](https://gitee.com/uploads/images/2018/0228/081037_eaf8d79f_930142.png "屏幕截图.png")

##### B、调整字号的快捷键 

**使用调整字号的快捷键时需要先全选文本，然后快捷键才可以生效**

MAC快捷键|Win快捷键|含义
-|-|-
cmd+shift+<|ctrl+shift+< |减小字号
cmd+shift+>|ctrl+shift+> |增大字号

##### C、使用字符面板实现特殊样式（全大写，全小写，角标，分数 等）
![](https://gitee.com/uploads/images/2018/0228/082301_c48a4a90_930142.png "屏幕截图.png")

##### D、批量修改文字图层中的文字内容

在右下角图层面板中，选择多个文字图层，然后再选择 **文字工具（T）** 即可对多个文字图层中的内容进行编辑。

##### E、载入路径选框
**按住 ctrl** ，然后 **单击** 右下角图层面板中 **指定图层的缩略图**，这样就可以载入选框

#### （4）、橡皮擦和画笔
橡皮擦（E）：擦除像素内容
画笔（B）：向画布中喷涂前景色

**在使用 画笔和橡皮擦工具 时， 配合 左右中括号按键 — —【 、 】可以快速的缩放画笔的大小**


#### （5）、绘制Banner  
具体步骤省略，此处只附上教程中的最终效果：
![](https://gitee.com/uploads/images/2018/0228/085438_0b328fdf_930142.png "屏幕截图.png")


## Day04 矢量形状与路径
20180228 

### 1、形状层和位图层区别
#### （1）、选框工具（M）绘制图形和路径绘制图形的区别
* 选框绘制的图形属于位图，形状绘制的图形属于矢量图
    * 位图由像素点组成，拉大之后会变模糊
    * 矢量图拉大之后不会模糊
    * **位图需要自己手动建立图层；矢量图会自动添加形状图层**


### 2、形状工具（U）的不同模式
#### （1）、形状工具（U）的模式分类
如下图所示，当我们选中 形状工具之后，在属性栏中点击 **路径** 后面的向下箭头可以看到，有三种模式 ：**路径、形状、像素**

![](https://gitee.com/uploads/images/2018/0228/203512_70f3b47f_930142.png "屏幕截图.png")

#### （2）、形状模式和路径模式的区别
* 路径模式只是绘制一个路径线（辅助功能），需要后期的操作（变选框、填充、描边等）（路径的绘制使用钢笔工具 P）
* 形状模式会自动建立图层（形状图层），并默认填充前景色
* 路径模式通常只用来抠图；形状模式则用来画图（UI构图）；像素模式基本使用不到

### 3、形状工具（U）的基本操作（形状模式）
#### （1）、基本换色操作
* **双击** 右下角图层面板中 形状图层 的 **缩略图**![](https://gitee.com/uploads/images/2018/0228/205519_8a37afb2_930142.png "屏幕截图.png")，可以快速调出调色板，选中某个颜色后可以直接 **更改画布中形状的颜色**。

#### （2）、形状工具的属性栏
* 形状工具属性栏概览：
![](https://gitee.com/uploads/images/2018/0228/205817_6d412ef2_930142.png "屏幕截图.png")

### 4、 形状工具属性栏详解

>**注意： MAC 和 Win下一致**
>
>* **绘制形状时，按住 shift 键再绘制，能够得到正XX形状（先按下鼠标左键不松，再按下shift键，然后拖动）**
>* **绘制形状时，按住 alt 键，可以由中心向四周绘制（需要先按下鼠标左键不松，再按下Alt不松，然后拖动）**

#### （1）、描边选项
![](https://gitee.com/uploads/images/2018/0228/210326_da639a22_930142.png "屏幕截图.png")

#### （2）、调整圆角矩形的圆角半径
* 在使用 形状工具（U）绘制圆角矩形时，需要 **先调整半径**，然后**再去**画布中**绘制**。
* 点击 **设置** 可以切换形状为 **正方形**

具体如下图：

![](https://gitee.com/uploads/images/2018/0228/212547_621849da_930142.png "屏幕截图.png")

#### （3）、切换椭圆形状为正圆
![](https://gitee.com/uploads/images/2018/0228/213023_79ef33f8_930142.png "屏幕截图.png")

#### （4）、设置多边形的边+绘制星型

* 在绘制 星型时 **缩进边依据**  的取值越大，角越尖锐；取值越小，角越钝
* 在绘制 星型时 **平滑拐角** 能用圆角替代尖角

![](https://gitee.com/uploads/images/2018/0228/213329_b6fa358f_930142.png "屏幕截图.png")

#### （5）、调整线段的宽度及线段的箭头
![](https://gitee.com/uploads/images/2018/0228/213646_4f7c2208_930142.png "屏幕截图.png")

#### （6）、创建并存储自定义形状
步骤如下：
* 绘制形状
* **编辑--定义自定形状**

### 5、形状属性练习--绘制播放器图标 V26 

利用形状属性绘制出下图的效果：

![](https://gitee.com/uploads/images/2018/0301/110122_e374f19b_930142.png "屏幕截图.png")

#### （1）、形状层的羽化

选区的羽化是 shift+F6 ,但是 **形状层的羽化则需要在属性面板中操作**，如下图：
* 先选中形状图层（点击下图的 1 区域）
* 点击形状的属性按钮（点击下图中的 2 区域）调出属性面板
* 切换到 蒙版面板（点击下图的 3 区域）    
* 调整羽化值（在下图的 4 区域 拖动滑块或者直接输入像素值）

![输入图片说明](https://gitee.com/uploads/images/2018/0301/100720_7ea039a3_930142.png "屏幕截图.png")

#### （2）、绘制播放器图标的步骤：

##### A：基本图形绘制
* 新建画布，填充一个较深的颜色，并另存为 psd 文件
* ctrl+r / cmd +r 打开标尺
* ctrl+t / cmd +t 调出自由变换工具，确定中心点，并依据中心点绘制中心辅助线
* 形状工具（U）-- 椭圆形状工具
* 在中心点位置按下鼠标左键不松，然后同时按下 shift 和 alt， 然后拖拽，得到一个填充了前景色的正圆（外层的大圆,）
* 重复上一步，再画一个稍小的正圆（内层小圆，临时填充一个与前景色不同的其他颜色，区分内外圆）
* 形状工具（U）-- 自定义形状 -- 从属性栏中找到 形状属性，然后从下拉菜单中找到 圆角三角形 并选中
* 在中心点位置按下鼠标左键不松，然后同时按下 shift 和 alt, 然后拖拽，得到一个圆角正三角形，为该三角形填充颜色。
* 使用 cmd+t / ctrl+t 自由变换工具调整三角形的箭头向右，并使用移动工具 (v) 适当调整位置

##### B：影子的绘制
* 选中外层圆图层，然后 ctrl + j /cmd+j 复制该图层，将复制出来的图层作为阴影层，
* 在图层面板中拖动阴影图层到外层圆图层下方
* 双击图层面板中，阴影图层前面的缩略图，选择黑色（或者深灰色）作为阴影图层的填充色
* 选择 移动工具（V），然后通过 上下左右键 调整阴影层相对于 外层圆的位置。
* 内层圆 和 三角形 绘制阴影图层的操作与上同理

##### C：设置光影效果
**在绘制播放器图标时，我们通常认为光是从顶部直射的，所以，内容的上方为高光区，下方为阴暗区域。**

设置光影效果时，可以直接使用 **形状工具 -- 填充 -- 渐变**，如下图：
![](https://gitee.com/uploads/images/2018/0301/092025_963d25a3_930142.png "屏幕截图.png")

* 在形状工具属性栏中，选择 填充--渐变--黑白渐变，
* 双击色标，调整颜色，选择一个较浅的颜色。
* 选中外层圆，在外层圆图层上绘制渐变色。
* 内层圆和三角形的光影效果与上同理

##### D:内层圆的内凹和描边
* 选中内层圆图层
* 在 形状工具（U）的属性栏中，选择 **填充 -- 渐变 -- 反向渐变颜色**，让内层圆的顶部颜色变为略深的阴影色，让内层圆的底部变为亮色，这样就根据光影效果得到了内凹的效果
* 在 形状工具（U）的属性栏中，调整 **描边** 属性的取值（约 6px 即可）
* 在 形状工具（U）的属性栏中，调整 **描边类型** 为 **渐变 —— 黑白渐变**，并调整颜色(描边的上方需要高光，因为，在绘制这个图标时，我们假定了光是从正上方投下的)。

描边宽度和描边形状的调整，如下图：

![](https://gitee.com/uploads/images/2018/0301/095239_8c0476d2_930142.png "屏幕截图.png")

##### E：阴影的优化

* 在右下角 图层面板 中 选中 外层圆阴影图层
* 调出属性面板（参考上面的 （1）形状层的羽化）
* 调整羽化值（调整完羽化值之后，阴影颜色依旧比较深)
* 在右下角图层面板中调整不透明度，参考下图
* 内层圆阴影和三角形阴影的调整与上同理
![](https://gitee.com/uploads/images/2018/0301/101103_9e1f878b_930142.png "屏幕截图.png")

##### F：绘制快进和快退按钮

MAC快捷键|Win快捷键|含义
--|--|--
cmd+G|ctrl+G|编组（先选中多个图层，然后按下该快捷键即可编组）

**快进按钮的绘制：**
* 在图层面板中，选中除背景层以外的全部图层
* 按下 Ctrl+G /Cmd+G，对选中的图层进行编组，命名为 播放按钮
* 按下 Ctrl+J /Cmd+J，复制编组，命名为快进按钮
* 选中 快进按钮编组 中的全部图层，并使用移动工具平移这些图层
* 选中 快进按钮编组 中的 三角图层 和 三角阴影图层，
* 使用 Ctrl+T / cmd+T 自由变换工具，调整 三角图层 和 三角阴影图层 的大小，按下回车键完成调整
* 按下 alt （win 与 mac 相同）键，复制 三角图层和三角阴影图层（复制之前必须确保这两个图层是被选中的）
* 调整复制出来的 三角图层 和 三角阴影图层的位置


**快退按钮的绘制：**
* 复制 快进按钮编组 ，命名为 快退按钮编组
* 选中四个三角图层（两个三角图层+两个三角阴影图层）
* ctrl+t/cmd+t 调出自由变换工具，此时 **右击，选择 水平翻转**，这样就得到了两个向左的三角。

##### G：对齐三个按钮
* 选中三个编组
* 选择移动工具（V）
* 在移动工具属性栏中 选择 **垂直居中对齐**

### 6、路径选择工具（A）——小黑功能 v27 
形状层 转换为 位图层：在形状层上右击--栅格化图层。（慎用）

#### （1）、路径选择工具（A）的分类：

* 路径选择工具--因为前面的箭头是黑色的，所以称为小黑
* 直接选择工具——因为前面的箭头是灰白色的，所以称为小白

#### （2）、路径选择工具（A）——小黑的作用

##### A：具体作用
其作用是：**选择并复制完整路径，并且复制时不会新建图层，而是和原路径在同一图层中**

##### B：使用步骤：
* 先使用形状工具（U）在界面上绘制一个形状
* 选择 路径选择工具（U），
* 按下 alt 键，左键拖动先前绘制的形状，完成路径的复制。复制出来的形状和原形状在同一个图层中

##### C：补充说明
如果想将复制出来的路径放置在新的图层中，可以在复制时使用如下方式：
* 使用 移动工具（V），在拖动时按住 alt 键。这样就会将复制出来的内容放在新的图层中
* 使用 ctrl+j / cmd +j 复制（这种方式慎用）

### 7、直接选择工具（A）——小白功能

#### （1）、选择锚点
使用直接选择工具选择锚点时有两种方式：
* 框选——鼠标在画布空白处点击并拖动，**拖动的范围需要将锚点涵盖。可以涵盖多个锚点**
* 点选——直接单击锚点可以选中；如果 **按住shift键再去单击锚点可以多选**

使用上面两种方式多选锚点之后，就可以同时操作这些锚点了。

#### (2)、调整手柄
* 通过拖拽手柄点可以调整路径线的弧度
* **按住 Alt 键，拖拽手柄点，可以只调整锚点一侧的路径线**，
    * 调整**另一侧**的路径线时**不需要再次按下Alt**
    * 基于以上，当我们再次 **需要两边的路径同时变化，则需要再按住Alt键**

>调整路径时的区别： 
>* 如果不按住alt键，拖动一方的手柄点调整路径时，另一方也会跟随变化，锚点两侧的手柄线始终保持为一条直线
> * 按住 alt 键，拖动一侧的手柄点调整路径时，另一侧不会跟随变化，也就是说，两侧手柄线的角度会任意变化 

### 8、钢笔工具补充 和 布尔运算 v29

#### （1）、钢笔工具（P）补充

![](https://gitee.com/uploads/images/2018/0302/090831_dbf20d0d_930142.png "屏幕截图.png")

如上图所示，钢笔工具除了用来绘制路径，还可以 **添加锚点、删除锚点、转换点**

##### A：转换点的作用
* 当我们使用 直接选择工具（A） 拖动锚点时，得到的实际是一个圆角图形
* 然后我们选择 钢笔工具（P）——转换点工具，然后单击圆角锚点，此时，圆角变为锐角。

##### B:使用技巧

* 使用 钢笔工具（P）时，按住 Ctrl / cmd ,会临时切换到小白工具
* 使用 钢笔工具（P）时，按住 Alt，会临时切换为转换点工具
* 使用 钢笔工具（P）时，光标放到锚点上，会变为 删除锚点工具
* 使用 钢笔工具（P）时，光标放到路径线上，会变为 新增锚点工具

作业1：

![](https://gitee.com/uploads/images/2018/0302/093323_3375a756_930142.png "屏幕截图.png")

#### （2）、布尔运算

##### A：什么是布尔运算
布尔运算对应 **形状工具（U）** 属性栏中的 **路径操作**，具体如下：
![](https://gitee.com/uploads/images/2018/0302/093800_4e00ad0c_930142.png "屏幕截图.png")

>最后一个合并形状组件，需要** 先执行其他操作时候才可以使用**，合并之后就变成了一个单一的图形，尽量不要使用

##### B：布尔运算的具体使用：
有如下两种方式：

**方式A：**
* 在属性栏中选择路径操作模式（即布尔运算模式）
* 绘制一个图形，
* 在属性栏中选择路径操作模式（即布尔运算模式）
* 绘制另一个图形（两个图形在同一个图层上，不需要新建图层）

**方式B：**
* 先绘制一个图形
* 新建图层并绘制第二个图形
* 选中两个图层然后合并（Ctrl+E / cmd +E）
* 用小黑（路径选择工具 A）选中要运算的图形
* 选择运算选项

**注意： 方式B中，相减时必须先选择一个图形，若选择两个图形，则是与整体画布的相减**

### 9、安卓 LOGO 绘制 V30 

重点：
* 配合 小黑移动路径 ，达到需要的效果。
* 两种布尔运算的灵活运用（先选模式，再去绘制！！！）


绘制最终效果图：

![](https://gitee.com/uploads/images/2018/0302/104836_bbeda0e9_930142.png "屏幕截图.png")

## Day05 图层样式详解
20180302 
### 1、哪些层可以添加图层样式？ V31
* **背景层**不能添加样式。
* **位图层、文字层、形状层、图层组** 等可以添加图层样式。

 ![](https://gitee.com/uploads/images/2018/0305/083813_386a898f_930142.png "屏幕截图.png")


### 2、图层样式的操作

#### （1）、样式面板的展示
窗口--样式

#### （2）、图层样式的基本操作

##### A：图层样式的添加

 ![](https://gitee.com/uploads/images/2018/0305/083813_386a898f_930142.png "屏幕截图.png")

##### B：图层样式的存储
先给图层**编辑**好一个样式，然后**选中该图层**，然后按照下列步骤操作：
![](https://gitee.com/uploads/images/2018/0305/085246_b07ea565_930142.png "屏幕截图.png")

##### C：删除整体的图层样式
![](https://gitee.com/uploads/images/2018/0305/090208_de5ce081_930142.png "屏幕截图.png")

##### D：删除其中的一个样式
![](https://gitee.com/uploads/images/2018/0305/090306_f033701f_930142.png "屏幕截图.png")

##### E：复制图层样式
![](https://gitee.com/uploads/images/2018/0305/090549_24af35e5_930142.png "屏幕截图.png")

### 3、图层样式选项介绍--投影和内阴影

##### A：投影
* 图层样式中的选项并不是只能做它名字指定的功能，还可以做其他的功能
* **勾掉**下图中的 **使用全局光** 可以**只调整当前图层**的光源角度。如果不勾掉的话，会应用于全部图层。
![](https://gitee.com/uploads/images/2018/0305/091051_c4025d3f_930142.png "屏幕截图.png")

##### B：内阴影
* 制作凹入凹陷的效果

### 4、内发光、外发光和叠加

##### A：外发光
![](https://gitee.com/uploads/images/2018/0305/092257_094d2858_930142.png "屏幕截图.png")

使用外发光可以制作如下效果：
![](https://gitee.com/uploads/images/2018/0305/092501_490036a2_930142.png "屏幕截图.png")

##### B：内发光
使用方法类似于外发光

##### C:三个叠加效果
叠加效果不能同时使用，否则，会被彼此覆盖。如果确实需要同时应用，必须降低不透明度。
![](https://gitee.com/uploads/images/2018/0305/092723_18d3f086_930142.png "屏幕截图.png")


### 5、定义图案
* 新建画布 约10X10PX
* 绘制图案图形
* **编辑--定义图案** 

**Alt+shift+Del** 直接填充前景色给当前图层中使用的自定义图案

##### A：练习：将下图作为自定义图案
![](https://gitee.com/uploads/images/2018/0305/202052_7300302c_930142.png "屏幕截图.png")

### 6、斜面和浮雕

主要用来制作立体效果、
![](https://gitee.com/uploads/images/2018/0305/202518_1488d37e_930142.png "屏幕截图.png")

### 7、描边
![](https://gitee.com/uploads/images/2018/0305/203517_ffd69387_930142.png "屏幕截图.png")

### 8、开心童年海报的绘制 V38
胖娃字体
文字--文字变形工具--扇形字体
复制文字图层，并描边+颜色叠加
渐变叠加--Ctrl+T 自由调整，将图层上移
shift+ctrl+I 反选

具体步骤待补充。

### 9、倚天屠龙记海报绘制 V39

魔棒--不连续
alt+shift+del 直接填充颜色到已有颜色的选区
斜面和浮雕
画笔绘制红色背景
具体步骤待补充。

### 10、电源插座海报绘制 V40

具体步骤待补充。

## Day06 色彩调整
### 1、文档的颜色模式

![输入图片说明](https://gitee.com/uploads/images/2018/0305/211132_f695eb73_930142.png "屏幕截图.png")


色彩的调整分为：调色和校色

#### （1）、修改颜色模式的方法

![输入图片说明](https://gitee.com/uploads/images/2018/0306/095915_b9ab5759_930142.png "屏幕截图.png")

RGB模式：红、绿、蓝 组成的各种颜色（即完整的色谱），应用于互联网
CMYK模式：青色、洋红色、黄色、黑色 组成的颜色，    应用于印刷行业
灰度模式：黑、白、灰组成的颜色。

![输入图片说明](https://gitee.com/uploads/images/2018/0305/212952_9bec2b5c_930142.png "屏幕截图.png")

### 2、颜色通道的意义
颜色通道是用来存储颜色信息的。

颜色通道分为：
* **复合通道**：以彩色显示的
* **单色通道**：以黑白灰或者红绿蓝或者青品黄显示

单色通道中 黑白灰 表示的意义如下：
* **黑**：表示存储色值最低（0）
* **白**：表示色值最高（255）
* **灰**：存储色值的区间为 （0，255），接近255为亮灰色，接近0 为暗灰色。


### 3、色彩基础
#### （1）、自己创建一个色相环
先画一个正圆，然后按照如下步骤操作：

![](https://gitee.com/uploads/images/2018/0306/093508_b610e81b_930142.png "屏幕截图.png")

![](https://gitee.com/uploads/images/2018/0306/093657_9d481860_930142.png "屏幕截图.png")

![](https://gitee.com/uploads/images/2018/0306/093849_3e5b5e91_930142.png "屏幕截图.png")

#### （2）、色相环的介绍
* **光的三原色**：红、绿、蓝
* **间色**：两个原色之间的颜色：黄色、青色、洋红色
* **反色（互补色）**：色相环中相对的颜色（即在180°线上的对称的颜色）。 **红反青、黄反蓝、绿反洋红**
* 复色：R、G、B通道中只要值都不为0，就是复色。


#### （3）、减淡工具（o）
* 减淡工具：让内容变亮
* 加深工具：让内容变暗

### 4、色阶（Ctrl+L/Cmd+L） V44
#### (1)、认识色阶
![](https://gitee.com/uploads/images/2018/0307/085529_234402f8_930142.png "屏幕截图.png")

#### （2）、色阶的功能

##### A：调整图片的明暗度
* 黑场右划，图片变黑/变暗
* 白场左划，图片变亮
* 灰场：只做轻微的调整。如果调整幅度较大，还是要用黑场或者白场
![](https://gitee.com/uploads/images/2018/0307/090402_08fa6f77_930142.png "屏幕截图.png")

##### 补充 A-1 :完美明暗度示例
**照片标准**：有高光，有暗调，有灰调，并且分布均匀。

符合上述标准的图片的大致色阶图如下：
![](https://gitee.com/uploads/images/2018/0307/092418_5c27a57d_930142.png "屏幕截图.png")

##### B：调整颜色（调整偏色的图片）
* Cmd+L/Ctrl+L打开色阶工具
* **选择** 通道中当前照片 **所偏重色相（或者反色相）** 对应的 **通道**
* **调整灰度划块**（不要动黑场和白场的划块）

##### B-1:调色需要判断的内容
* 判断偏重于什么颜色（红、青 ；绿、洋红；蓝、黄）
    * 如果是偏重于 红、绿、蓝，则选择对应的单色通道即可。
    * 如果是偏重于 青、洋红、黄，则选择对应的反色相通道。

### 5、色阶补充
Shift+Ctrl+I 反向选择。
#### （1）、局部调色
**用选框和其他工具配合色阶可以实现局部调色。**

#### （2）、快速调整明暗度和清晰度
通过 **黑场吸管 和 白场吸管** 可以快速调整图片的明暗度和清晰度。

注意：**黑场吸管和白场吸管不要点击在任何有彩色的地方（需要点击在无色相的地方 -- 黑白灰区域）！**

使用步骤如下：
* 打开图片
* 选择 **黑场吸管** ，在图片中需要展示为黑色（或纯黑色）的地方单击
* 选择 **白场吸管** ，在图片中需要展示为白色（或纯白色）的地方单击
* 按照前面两步选择完成之后软件会自动调整。

![](https://gitee.com/uploads/images/2018/0307/101004_1ef833fc_930142.png "屏幕截图.png")

### 6、曲线（ctrl+M /Cmd+M）

#### （1）、整体调整亮度/清晰度
![](https://gitee.com/uploads/images/2018/0307/110528_299596ef_930142.png "屏幕截图.png")


#### （2）、部分调整亮度/清晰度

![](https://gitee.com/uploads/images/2018/0307/110908_f1b00d31_930142.png "屏幕截图.png")

#### （3）、调整颜色（单通道调整）
![](https://gitee.com/uploads/images/2018/0307/112435_cc3f8570_930142.png "屏幕截图.png")

#### （4）、调整指定位置
![](https://gitee.com/uploads/images/2018/0307/113046_66e9e5f8_930142.png "屏幕截图.png")

#### （5）、其他调整方式
![](https://gitee.com/uploads/images/2018/0307/113228_ba2992dc_930142.png "屏幕截图.png")

![](https://gitee.com/uploads/images/2018/0307/113447_866c0e98_930142.png "屏幕截图.png")

![](https://gitee.com/uploads/images/2018/0307/113736_f313c8c7_930142.png "屏幕截图.png")

### 7、色相饱和度 Ctrl+U/Cmd+U
#### (1)、基本介绍
![](https://gitee.com/uploads/images/2018/0308/083757_3924f371_930142.png "屏幕截图.png")

颜色的三个属性：色相（简写H）、饱和度（简写S）、明度（简写B）
* 色相：颜色的色值
* 饱和度：颜色的鲜艳程度。饱和度为0时，所有颜色都变为黑白灰
* 明度：颜色的亮度。明度为0时，所有颜色都变为黑色。



#### （2）、整体着色
勾选 着色 之后，图片整体会变为单一色调风格。
![](https://gitee.com/uploads/images/2018/0308/084752_c5e45ffb_930142.png "屏幕截图.png")

#### （3）、调整某一种颜色
步骤如下：

* 在 色相/饱和度 面板中选择单色模式（默认是全图模式）
* 选中吸管工具
* 在图片中单击需要改变的颜色
* 调整色相、饱和度、明度

按照如上步骤就可以将红色的花变成紫色：

**A：调整前**
![](https://gitee.com/uploads/images/2018/0308/090303_a080f629_930142.png "屏幕截图.png")

**B:调整后**
![输入图片说明](https://gitee.com/uploads/images/2018/0308/085944_ac7876cb_930142.png "屏幕截图.png")

### 8、色相饱和度案例

#### （1）案例1——部分突出展示
* **需求**：将下图中人物及背景区域颜色减淡，将花朵区域增强，突出显示花朵
* **知识点**：路径、路径变选区（ctrl+enter / cmd+enter）、选区反选（ctrl+shift+I / cmd+shift+I）、色相饱和度


**A：原图：**

![](https://gitee.com/uploads/images/2018/0308/094314_a8b331f7_930142.png "屏幕截图.png")

**B：效果图：**

![](https://gitee.com/uploads/images/2018/0308/094107_c2fce0f9_930142.png "屏幕截图.png")

**C：绘制步骤**
* ctrl+J / cmd+J 复制图层（修改内容时在复制的图层上操作，原图不要动）
* 使用钢笔工具绘制花瓣的路径
* 将路径变为选区 ctrl+enter / cmd+enter
* ctrl+shift+I / cmd+shift+I 反选除花瓣以外的区域
* 调整花瓣以外区域的饱和度，向左降低饱和度让人物及背景区域整体偏灰白
* 再次 ctrl+shift+I / cmd+shift+I 选中花瓣区域
* 调高花瓣区域的饱和度和明度

#### （2）、案例2——四分图
* **需求**：图片分为四个不同色相的区域
* **知识点**：标尺（ctrl+R/Cmd+R）、辅助线（借助自由变换工具实现 cmd+t /ctrl+t）、辅助线的显示和隐藏（ctrl+； / cmd +；）、选区、色相饱和度

**A:原图**

![](https://gitee.com/uploads/images/2018/0308/095456_cf2d432a_930142.png "屏幕截图.png")

**B：效果图**

![](https://gitee.com/uploads/images/2018/0308/100935_c1a0e2e5_930142.png "屏幕截图.png")

**C:绘制步骤**

* 绘制标尺和辅助线
* 基于辅助线选区，调整选区内的色相饱和度(重复四次）

### 9、综合应用
* 调低背景的饱和度和明度，降低其色彩
* 橡皮工具--不透明度，然后调整侧脸图人物周边，降低人物周边更加柔和，达到近似羽化的效果
* 添加牡丹背景
* 添加文字和印章

#### (1)、素材和效果示例：素材源于网络

![](https://gitee.com/uploads/images/2018/0308/103838_37bf2018_930142.png "屏幕截图.png")

![](https://gitee.com/uploads/images/2018/0308/104207_15755248_930142.png "屏幕截图.png")

![输入图片说明](https://gitee.com/uploads/images/2018/0308/104339_7affa3f0_930142.png "屏幕截图.png")

![输入图片说明](https://gitee.com/uploads/images/2018/0308/104457_95e063b5_930142.png "屏幕截图.png")

最终效果图：
![](https://gitee.com/uploads/images/2018/0308/103510_6050cd5e_930142.png "屏幕截图.png")

#### （2）、我的效果图：
![](https://gitee.com/uploads/images/2018/0309/102610_2c6360e0_930142.png "屏幕截图.png")

绘制步骤：
* 新建画布，并另存为PSD文件
* 植入背景图，降低其饱和度(将背景图变成近似水墨画的效果）
* 打开侧脸图，使用选区工具（可以使用 魔棒、快速选区 或者 套索工具 或者钢笔工具）快速抠图
* 将抠出来的侧脸图植入到画布中
* 橡皮擦工具（E）--属性栏——常规画笔——柔边缘。硬度改为0，调整像素大小。降低不透明度，改为35左右。在侧脸图周边涂抹，达到羽化效果.橡皮擦的配置如下图：
![](https://gitee.com/uploads/images/2018/0309/104639_9830bce4_930142.png "屏幕截图.png")
* 抠取牡丹图，并植入到画布
* 使用橡皮擦工具制作牡丹的羽化效果
* 抠取双人图，并植入画布
* 使用橡皮擦工具制作人物腿部的羽化效果
* 插入文字


## Day07 图层混合模式和图层蒙版
### 1、混合模式的使用条件
**混合模式**：即 图层与图层之间通过某种计算方式，得到一个新的画面。

使用条件：

* 必须有两个或多个图层
* 必须将所有素材都放到同一个画布上

### 2、重点混合选项 v51
#### （1）、溶解（使用较少）
使用时 **必须先降低图层的不透明度**，使用之后图层会出现小颗粒效果（即磨砂效果）

![输入图片说明](https://gitee.com/uploads/images/2018/0309/194647_fa80de5a_930142.png "屏幕截图.png")

#### （2）、正片叠底（使用较多）
去亮色，留暗色
即：将明度高的颜色的透明度变为0

##### A:无色相时的效果
在下图中，**去亮色，留暗色**的体现时：
* 黑色还是黑色（留暗色）
* 灰色变成了透明的灰色（去亮色，即将其透明度变为0）
* 白色则完全成了透明色（去亮色，即将其透明度变为0）

![](https://gitee.com/uploads/images/2018/0309/201157_0a018d17_930142.png "屏幕截图.png")

##### B：有色相时的效果
正片叠底有色相时，找到当前图层颜色的暗色调

![](https://gitee.com/uploads/images/2018/0309/202606_ba2b982b_930142.png "屏幕截图.png")


#### （3）、颜色加深
和正片叠底功能类似，程度大于正片叠底。

![](https://gitee.com/uploads/images/2018/0309/204048_4ec36eca_930142.png "屏幕截图.png")

![](https://gitee.com/uploads/images/2018/0309/204611_be9fce19_930142.png "屏幕截图.png")

#### （4）、补充：反相
Ctrl+I / CMD + I 反相（调整颜色为其反相颜色）
![输入图片说明](https://gitee.com/uploads/images/2018/0310/182417_3ff68e63_930142.png "屏幕截图.png")

### 3、滤色 和 颜色减淡 讲解 V52

#### （1）、滤色
滤色：
***去暗色，留亮色**（与正片叠底相反）

* 有色相时，找到当前图层颜色的亮色调。

###### A、无色相时的效果
* 原图
![](https://gitee.com/uploads/images/2018/0310/183339_a7605aa4_930142.png "屏幕截图.png")

* 效果图
![输入图片说明](https://gitee.com/uploads/images/2018/0310/183518_1d5a1eb2_930142.png "屏幕截图.png")

##### B、有色相时的效果
* 原图
![](https://gitee.com/uploads/images/2018/0310/184054_d930775b_930142.png "屏幕截图.png")

* 效果图
![](https://gitee.com/uploads/images/2018/0310/184024_09299321_930142.png "屏幕截图.png")


##### C、案例：为衣服添加LOGO
素材：
![](https://gitee.com/uploads/images/2018/0310/184424_c8253a95_930142.png "屏幕截图.png")

![](https://gitee.com/uploads/images/2018/0310/184455_12b85a4b_930142.png "屏幕截图.png")

###### A：黑色Logo效果：
![](https://gitee.com/uploads/images/2018/0310/185129_d5bcc997_930142.png "屏幕截图.png")

绘制步骤和要点：
![](https://gitee.com/uploads/images/2018/0310/185059_88fe7dcd_930142.png "屏幕截图.png")


###### B：白色LOGO效果
![](https://gitee.com/uploads/images/2018/0310/185255_a65cf34c_930142.png "屏幕截图.png")

绘制步骤和要点：
![](https://gitee.com/uploads/images/2018/0310/185600_dcd3551d_930142.png "屏幕截图.png")

#### （2）、颜色减淡
**和滤色功能相同，但是程度大于滤色**。（可参考 正片叠底 和 颜色加深的关系）

### 4、叠加
叠加之后的效果是：**亮的更亮，暗的更暗**

原图效果：
![](https://gitee.com/uploads/images/2018/0310/200416_c69abe73_930142.png "屏幕截图.png")

叠加之后的效果：
![](https://gitee.com/uploads/images/2018/0310/201015_7cc34310_930142.png "屏幕截图.png")

![](https://gitee.com/uploads/images/2018/0310/201311_118f4c7a_930142.png "屏幕截图.png")

![](https://gitee.com/uploads/images/2018/0310/201549_e050121f_930142.png "屏幕截图.png")

![输入图片说明](https://gitee.com/uploads/images/2018/0310/201951_38d7d564_930142.png "屏幕截图.png")



#### （1）、制作高光效果案例——雷电
##### A：素材：
![](https://gitee.com/uploads/images/2018/0310/195956_e3409e0a_930142.png "屏幕截图.png")


![](https://gitee.com/uploads/images/2018/0310/200028_8cf20eaf_930142.png "屏幕截图.png")

##### B:效果图
![](https://gitee.com/uploads/images/2018/0310/195913_752f1501_930142.png "屏幕截图.png")

##### C：绘制流程

###### C-1、局部变亮的绘制

* 打开乌云图层，并新建一个图层——用来做局部变亮效果，
* 前景色调为白色，使用 渐变工具--前景色到透明的渐变，在需要局部变亮的位置绘制 渐变色
* 选中局部变亮图层，并选择叠加模式

![](https://gitee.com/uploads/images/2018/0310/202823_1a883092_930142.gif "局部变亮.gif")
* 

###### C-2、闪电的处理

* 将闪电素材图层拖拽到乌云界面中
* 选中闪电图层，Ctrl+L / CMD +L 调出色阶工具，将黑场和灰常右移，增大暗色调
![](https://gitee.com/uploads/images/2018/0310/203420_f6e1eb6a_930142.gif "闪电.gif")

* 使用 滤色 模式，将闪电和乌云融合
![](https://gitee.com/uploads/images/2018/0310/204830_eeb889b9_930142.gif "闪电2.gif")
* 使用 Ctrl+T / cmd+T 自由调整工具调整闪电的大小和位置
* **最后再使用 Ctrl + Shift + U / CMD + Shift +U 去色工具，去除闪电图层中的紫色色素。**

Ctrl + Shift + U / CMD + Shift +U 去色

Ctrl +L 色阶

#### （2）、懒人调色法（快速调整图像清晰度）

**Ctrl+J / CMD +J 复制背景图层，然后使用叠加工具**

原图效果：
![](https://gitee.com/uploads/images/2018/0310/205627_f61435bb_930142.png "屏幕截图.png")

懒人调色之后的效果：
![](https://gitee.com/uploads/images/2018/0310/205729_1a50d5ed_930142.png "屏幕截图.png")

#### （3）、叠加组中的其他工具
![](https://gitee.com/uploads/images/2018/0310/205907_0f3e405c_930142.png "屏幕截图.png")

在上图中，这些模式和叠加在同一个组中，其效果与叠加基本类似，只是比叠加颜色略深或略浅

### 5、其他了解（使用较少的内容）V54

**Ctrl+Shift+U /CMD +Shift +U 将彩色图变为黑白颜色，达到底片的效果**

![](https://gitee.com/uploads/images/2018/0310/210149_cba01ee2_930142.png "屏幕截图.png")

## Day08 图层蒙版
### 1、蒙版基本概念 v55

#### （1）、作用：
* 多用于图形合成
* 图层蒙版可以替代橡皮擦功能，比橡皮擦功能更加灵活

#### （2）、应用范围
* 背景图层不能加蒙版，
* 蒙版多用于普通层、文字层、形状层、图层组上

#### （3）、如何添加蒙版：
![](https://gitee.com/uploads/images/2018/0311/191538_716eeb68_930142.png "屏幕截图.png")

![](https://gitee.com/uploads/images/2018/0311/190314_17bd3104_930142.png "屏幕截图.png")

#### （4）、蒙版填充色的含义：
* **白色**：显示当前图层
* **黑色**：隐藏当前图层
* **灰色**：将当前图层变为半透明

#### （5）、可以为蒙版上色的工具：
* 背景色/前景色 填充工具
* 画笔工具（B）
* 渐变工具（G）
* 图案工具
* 复制和粘贴功能

##### A：背景色/前景色填充
![](https://gitee.com/uploads/images/2018/0311/192545_80665374_930142.png "屏幕截图.png")

##### B：画笔工具填充
![](https://gitee.com/uploads/images/2018/0311/193018_abc6bb24_930142.png "屏幕截图.png")

##### C：渐变工具填充
![](https://gitee.com/uploads/images/2018/0311/193401_22dc3cd1_930142.png "屏幕截图.png")


### 2、使用蒙版需要注意的问题
* 必须要选中蒙版（选中之后，蒙版缩略图会有边框）
* 前景色需要设置为黑色，这样为蒙版上色时才能显示背景层中的内容。
* 如果设置为白色，涂抹时不会显示背景层中的内容，因为白色表示显示当前图层内容
* 如果设置为白色和黑色之外的颜色，都会被当做灰色处理
* 将需要合成的内容放到同一个文档中

### 3、蒙版高级应用

#### （1）、停用图层蒙版
**按住 Shift 键，在蒙版缩略图上单击即可停用蒙版（停用之后，蒙版缩略图上会显示一个红色X），
再次单击(不需要按住shift键)，即可启用**

![](https://gitee.com/uploads/images/2018/0311/195115_4465a6bc_930142.gif "禁用和启用.gif")

#### （2）、删除图层蒙版
直接拖拽蒙版缩略图到回收站即可
![](https://gitee.com/uploads/images/2018/0311/200326_d620ff98_930142.gif "删除蒙版.gif")

#### （3）查看蒙版颜色分布

* 按住Alt键，单击蒙版缩略图可以查看蒙版的颜色分布。
* 单击该蒙版对应的图层条目，可以重新展示图层内容

##### A：单击之前的效果
![](https://gitee.com/uploads/images/2018/0311/200910_1ee99989_930142.png "屏幕截图.png")

##### B：单击之后的效果
![](https://gitee.com/uploads/images/2018/0311/200810_47aebef8_930142.png "屏幕截图.png")

#### (4)、解除蒙版与图层的连接关系
单击他们之间的锁链图标即可。

##### A:解除蒙版关系前后的对比
测试步骤：
* 使用选区工具在蒙版图层中绘制矩形选框，然后填充黑色，然后 Cmd+D /Ctrl+D 完成选区
* 选中蒙版缩略图，并使用移动工具（V）拖动主工作区图层。（此时整个图层会产生移动，参考下面解除之前的动图）
* 点击锁链图标，解除链接关系
* 选中蒙版缩略图，使用移动工具庹宗主工作区图层。（此时，只有选区部分产生移动，参考下面的 解除之后的动图）

解除之前：
![](https://gitee.com/uploads/images/2018/0311/211931_e837ca8a_930142.gif "解除蒙版的影响2-1.gif")

解除之后：
![](https://gitee.com/uploads/images/2018/0311/202645_862858aa_930142.gif "解除蒙版的影响2.gif")


### 4、恶搞案例

### 5、重现三国案例

#### （1）素材：
乌云
![](https://gitee.com/uploads/images/2018/0312/153408_c9ad6872_930142.png "屏幕截图.png")
箭楼
![输入图片说明](https://gitee.com/uploads/images/2018/0312/153458_87009bed_930142.png "屏幕截图.png")
厮杀
![](https://gitee.com/uploads/images/2018/0312/153557_e29043e3_930142.png "屏幕截图.png")
旗帜
![](https://gitee.com/uploads/images/2018/0312/153626_773263aa_930142.png "屏幕截图.png")
书法字
![](https://gitee.com/uploads/images/2018/0312/153655_5ecd7242_930142.png "屏幕截图.png")
墨点
![](https://gitee.com/uploads/images/2018/0312/153717_1f32d73c_930142.png "屏幕截图.png")

#### （2）、绘制步骤
##### A：基本素材合成
* 新建画布，并依次放入 乌云、箭楼、厮杀 素材。并按下图样式排列：
![](https://gitee.com/uploads/images/2018/0312/154411_11a87ae0_930142.png "屏幕截图.png")
* 使用蒙版工具将箭楼图层、厮杀图层合成到乌云层中。合成时，使用画笔柔边圆为蒙版上色，可以将柔边圆的像素调的大一点，这样可以具有羽化效果。
![](https://gitee.com/uploads/images/2018/0312/155036_32db4345_930142.png "屏幕截图.png")

##### B：合成旗帜
* 抠取旗帜，并将其移动到目标文件中，然后使用 **魔棒工具（W）**选中白色背景区域，然后按 Del 键删除白色背景，再按 Ctrl+Shift+U 去除边缘杂色，然后调整旗帜大小，将其放在箭楼上。
![输入图片说明](https://gitee.com/uploads/images/2018/0312/155342_43911bbd_930142.png "屏幕截图.png")
* 复制旗帜图层，使用叠加效果让旗帜颜色更加鲜艳。然后 Ctrl+E /Cmd+E将三个旗帜图层合并
![](https://gitee.com/uploads/images/2018/0312/155803_67661194_930142.png "屏幕截图.png")

##### C：合成闪电
* 将闪电拖到文件中，然后 Ctrl+Shift+U 去色，将其变为黑色图片。
![](https://gitee.com/uploads/images/2018/0312/160207_f8fbd37a_930142.png "屏幕截图.png")
* 调整闪电图层的色阶，让亮的更亮，暗的更暗
![](https://gitee.com/uploads/images/2018/0312/160338_7b2f98fc_930142.png "屏幕截图.png")
* 使用 滤色工具 去除闪电图层中的黑色内容区域，仅保留闪电
![](https://gitee.com/uploads/images/2018/0312/160614_d107e3e4_930142.png "屏幕截图.png")
* 为闪电图层增加蒙版，去除多余的内容
![](https://gitee.com/uploads/images/2018/0312/160834_af72f0d2_930142.png "屏幕截图.png")

##### D:基本素材调整

* 将除 旗帜以外的全部图层 使用  Ctrl+Shift+U / Cmd+Shift+U 改为 黑白色
![](https://gitee.com/uploads/images/2018/0312/161403_bf249fdf_930142.png "屏幕截图.png")
* 将旗帜图层置为不可见，然后 Ctrl+Alt+Shift+E / shift+Cmd+E 合并其余可见图层。
* 使用画笔工具实现 **压边**效果。做压边效果时使用 画笔工具--柔边圆，将画笔像素调的大一点，用画笔的边缘去压边，从而达到羽化效果。压边的操作参考下面的GIF,整个边缘都去压边，达到突出中心内容的效果
![](https://gitee.com/uploads/images/2018/0312/181440_aab3c6a1_930142.gif "压边2.gif")
* 压边之后 使用 **Ctrl+B /Cmd+B 色彩平衡工具** 调整内容区域为青色效果.(使用 Ctrl+L / cmd +L 色阶工具也可以)
![](https://gitee.com/uploads/images/2018/0312/182730_8e97c86a_930142.png "屏幕截图.png")


##### E：文字素材合成
* 将文字素材拖到文件中，
* 魔棒工具选中白色区域（此处注意勾去属性栏中的 **连续**），然后按Del删除白色背景，然后alt+shift+del去除边缘杂色。然后使用Ctrl+T 调整文字大小，效果如下图：
![](https://gitee.com/uploads/images/2018/0312/193707_4b3dbf09_930142.png "屏幕截图.png")
* 新建图层，然后将前景色调为 橙色，然后用 画笔工具--柔边圆 在界面中绘制一条短线，然后使用 Ctrl+T 自由变换工具横向拉伸，如下图：
![](https://gitee.com/uploads/images/2018/0312/193957_91892750_930142.png "屏幕截图.png")
* 新建图层，然后将前景色调为 暗红色，然后用 画笔工具--柔边圆 在界面中绘制一条短线，然后使用 Ctrl+T 自由变换工具横向拉伸。然后移动该红色线条覆盖住上一步绘制的橙色线条的上半部分。如下图：
![](https://gitee.com/uploads/images/2018/0312/194851_f6c48385_930142.png "屏幕截图.png")
* 合并两个彩色线条图层。选中合并后的图层，然后 Ctrl+Alt+G /Cmd+Alt+G 剪切蒙版。（实现剪切蒙版时，需要将文字图层放到色彩图层下方）。效果如下：
![](https://gitee.com/uploads/images/2018/0312/195208_f0382fc7_930142.png "屏幕截图.png")
* 调整 重 和 国 字的大小
![](https://gitee.com/uploads/images/2018/0312/195945_8bfdbdca_930142.png "屏幕截图.png")
![](https://gitee.com/uploads/images/2018/0312/200048_899f646d_930142.png "屏幕截图.png")

##### F：添加高光区
* 新建图层
* 前景色置为白色，使用渐变工具绘制一个渐变区域
* 将该图层的混合模式设置为 叠加，行程高光区，并调整其位置
![](https://gitee.com/uploads/images/2018/0312/200537_a069788d_930142.png "屏幕截图.png")

###### G：添加墨点素材
* 使用选区工具抠选一个墨点，然后拖到文件中
* 使用魔棒选中白色背景区域，然后删除白色背景，并 alt+shift+del 去除边缘杂色
* Ctrl+U 使用色相/饱和度工具，将墨点调整为灰色
![](https://gitee.com/uploads/images/2018/0312/201000_c9f576e8_930142.png "屏幕截图.png")
* 使用 Ctrl+U 色相/饱和度工具，选中着色，将墨点调整为红色，并调整其大小和位置
![](https://gitee.com/uploads/images/2018/0312/201126_c619f0b1_930142.png "屏幕截图.png")
* 再加一个墨点，按照上一步描述改为红色，并调整位置和大小。最终效果如下：
![](https://gitee.com/uploads/images/2018/0312/201504_ec9053b0_930142.png "屏幕截图.png")



快捷键|含义
--|--
Ctrl+G| 编组
Ctrl+Shift+U| 去色 变为黑白图片
Ctrl+I |反相
Ctrl+Shift+Alt+E |盖印（即 合并可见图层，MAC下为：Shift+Cmd +E ）
Ctrl+L |色阶  
Ctrl+B |色彩平衡 
Ctrl+ [ |将图层想上移动
Ctrl+ ] |将图层向下移动
X |切换前景色/背景色
D |默认黑白前后背景色
alt+shift+del |去除抠图时的边缘杂色
Ctrl+Alt+G |剪切蒙版（需要剪切作为蒙版的图层在上，基本图层在下）。解除编组也是这个快捷键


## Day09 修图和滤镜

### 1、精确裁剪图片

#### （1）、证件照的制作
使用 **裁剪工具（C）** 

##### A:证件照尺寸介绍
证件照的标准尺寸：分辨率设置为 300 或 350 像素/英寸

* 一寸：2.5*3.5cm

* 五寸：12.7*8.9cm

##### B：相关快捷键
* **菜单栏 快捷键的使用**：Alt+菜单后面的快捷键字母。如：文件后面跟的字母是 F，则其快捷键为 Alt+F 

* Ctrl+alt+0 100%显示图片
* Ctrl+1 100%显示图片（同上）

##### C:一寸照片制作步骤
素材：
![](https://gitee.com/uploads/images/2018/0313/091228_9964583d_930142.png "屏幕截图.png")

步骤：

* 选择 **裁剪工具（C）**，然后选择 **宽X高X分辨率** 模式，依次填充 宽 2.5cm, 高 3.5cm , 分辨率 300 像素。此时，界面中会出现网格
* 拖动图片，调整需要留存的部分——网格中展示的就是最终留存的。（拖动时注意，不需要切换到移动工具，直接将光标指向网格区域内，光标会变成黑色实现箭头，直接按住鼠标左键拖动即可）
* 网格大小也可以调整，调整之后也可以选择需要留存的区域（拖拽网络边缘的粗线或者四个角上的粗线）
* 调整完留存范围之后回车即可。

![](https://gitee.com/uploads/images/2018/0313/091506_1882987c_930142.png "屏幕截图.png")

### 2、照片拼版及报名图片
* 透视照片裁剪
透视裁剪工具：

先在画布上回执一个网格，把每个点拖到照片的四个角上，回车。


