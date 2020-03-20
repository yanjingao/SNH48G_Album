# SNH48G_Album
SNH48G相册APP，提供海量图片和音乐，按成员分类图片，目前急需志愿者挑选成员优质图片

觉得有用的话请打上小星星☆☆☆  

作者QQ：1574927859  
如果有任何关于APP的意见和建议，请联系作者。  
如果想承担下面所说的志愿者工作，也请联系作者。  

## 一. 项目说明
### 1. APP下载
    “SNH48G相册.apk”即为APP。
### 2. 初始图库来源
    https://github.com/yanjingao/SNH48G_weibo_album
### 3. 志愿者列表
#### （1）SNH48-易嘉爱： 眼镜獒（项目作者）

## 二. 志愿者招募  
    招募志愿者承担挑选优质图片的工作。挑选后的效果见APP中上述志愿者列表中的成员。  

### 1. 为什么
    SNH48G成员的图片主要来源于成员微博，而成员微博的相册配图太杂，有很多不是成员优质的自拍照、而是截屏、糊图、表情包等，所以急需人员来挑出这些优质的自拍照，供大家使用，包括制作视频、制作网站等。本项目为开源项目，需大家一起努力。 也请大家多多宣传此项目。 

### 2. 怎么做
#### （1）联系作者
    做志愿者工作前先联系上作者，由作者协调工作，QQ在上面已给出。

#### （2）下载图片
    下载“SNH48所有成员微博图片链接（精选）.zip”，解压，里面为各个成员的微博相册图片链接，下载图片方法分为如下两类：  
    （注：图片文件名需为对应图片链接中的文件名，迅雷默认如此，用别的下载器或自己写脚本的需注意）
     + 1. 非程序员：用支持多行链接下载的下载器（比如迅雷）下载图片。此处给出迅雷的下载图片方法：打开txt文件，全选，复制，打开迅雷，新建任务，粘贴图片链接（迅雷可能自动帮你粘贴），如果最后一行是空行则删除空行，合并为任务组，可以改个名，然后下载。注：如果迅雷出现重复链接的提示，表示这次的图片链接里有一部分以前下载过，如果想下载重复的，只要把之前可能重复的任务删除，重新下载图片就可以了。  
     + 2. 程序员：自己写个多线程脚本下载，如果不愿写可以直接用https://github.com/yanjingao/SNH48G_weibo_album中的“download.py”，网速和线程数够的话比迅雷快很多。

#### （3）挑选优质图片
    把图片文件夹中所有非优质图片删除。推荐方法如下：
    打开图片文件夹，按文件大小排序，打开第一张图片，然后用“←”键控制“→”键控制图片切换，用“Delete”删除非优质图片，直至最后一张图片。  
整个过程可能比较累，尤其是对于图片多的成员。
  
#### （3）结果反馈
    在保证图片文件夹中只有优质图片后，将“双击此文件保存当前目录下所有文件名至files点txt文件.bat”文件（不是病毒，功能为输出当前目录所有文件名至files文件，代码只有三行，不信任的话可以右键记事本打开）放入图片文件夹，双击，在图片文件夹出现files.txt文件后（很快，不到一秒），关闭黑框，然后将files.txt文件发给作者。其余的事都交给作者，包括还原图片链接、图库更新等。
