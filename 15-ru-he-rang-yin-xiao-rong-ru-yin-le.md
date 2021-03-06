---
description: 看看红色区域里有哪些音效设置
---

# 15 如何让音效融入音乐

在介绍音效的各种功能之前先要插一句话。在所有的声音有关的设置里面都会出现一个小扳手的按钮，点开之后可以设置声音的音量（也就是声音大小），音高（也就是音调高低）和声像（也就是左右声道），这些设置别看好像藏得有点深，但其实用得巧妙的话是能极大提升关卡的细节感的。

同时还有一个文件夹按钮，可以支持你插入自定义的音效文件，格式必须是.ogg。如果要导入其他游戏里面的音效文件会很方便。如果要自己制作一个音频文件，要注意不要给音效文件前面留空白的时间，这样放在游戏里会感觉到音效出现延迟。

前面的铺垫完，接下来本节要介绍的主要是下面这四个功能：播放音效，设置按拍音效，设置游戏音效以及设置节拍音效。

## 设置节拍音效

如果你还有印象的话，在添加一个人物之后，里面就自带了一个设置节拍音效的选项：

如上图所示，沙锤就是少年登场之后出现的节拍音效。如果你想在中途改变少年的音效，就需要在红色的界面里面添加一个“设置节拍音效”物块，然后在轨道里面选择少年，在音效里选择其他的。

点一下下面的“复制轨道节拍音效设置”，就会把添加人物时设置好的节拍音效（包括音量音高声像）的具体内容全部粘贴到这个物块里面来。

## **设置按拍音效**

在编辑器中节拍音效和按拍音效是分开设置的。想要改变按拍时候的音效用的就是这个“设置按拍音效”，里面普通轨道（七拍子）和单发轨道（二拍子）又是分开设置的。但是不能对每一个人物单独设置，这一点需要注意。

## **设置游戏音效**

除了节奏音效和按拍音效之外，游戏里还有一些地方会出现音效，主要是失误的时候（分为微小失误和严重失误），没有节拍却按了空格的时候（默认是“啵”一声，所以在编辑器里面叫“手掌-啵音”），第七拍按下之后第八拍“咚”地一声回音（叫做心爆，这时候心脏图标也会小抖一下）。

这些音效在设置的时候是无法下拉列表选择更改的，只能通过键入游戏内置的音效文件名，或者导入自定义的音效来改变。

## **心爆**

在这里多说一句，如果你不喜欢第八拍的心爆声音，或者要做的关卡并不需要这个，那么就在红色界面的“设置心跳音量”里面把它改成0%。

另外，如果你想改变那个心爆声音延迟的时间（默认是在第八拍），就在红色界面的“设置心爆间隔”里面修改数值。

## **播放音效**

这是所有音效设置里面自由度最高的一个，可以在任意的时间开始播放一个音效文件，和游戏的轨道与按键没有任何关联。如果处理得当，你甚至可以用这个功能写一个打击乐段在游戏里面。

另外，剧情模式里面的内置音效也可以在这里通过写文件名的形式添加进自己的谱面。但是官方目前并没有公开所有的音效文件，我们收集了其中的一部分放在了附录3中整理成了表格，需要的话可以自取。

