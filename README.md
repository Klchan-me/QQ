# QQ For iOS
（UI界面使用纯代码 的Autolayout 布局，所以支持系统版本为IOS6.0以上）

<img src="https://github.com/weida-studio/QQ/blob/master/Sceenshots/screenShots.gif" width="320">

## Overview
QQ Code For iOS  >=IOS 6.0

Third Part Library:

- [PureLayout（非常灵活的自动布局第三方框架）](https://github.com/smileyborg/PureLayout)
- [SDWebImage（网络加载图片）](https://github.com/rs/SDWebImage)
- [FDTemplateLayoutCell (TableViewCell 动态计算高度)](https://github.com/forkingdog)
- [ODRefreshControl(高仿QQ的下拉刷新控件)](https://github.com/Sephiroth87/ODRefreshControl)



//数据源

WSChatModel *model1 = [[WSChatModel alloc]init];
model1.chatCellType=WSChatCellType_Text;
model1.isSender=1;
model1.content=@"聊了这么久还不知道你啥样子呢?";

WSChatModel *model2 = [[WSChatModel alloc]init];
model2.chatCellType=WSChatCellType_Text;
model2.isSender=0;
model2.content=@"我不喜欢自拍的,我跟我朋友以前在一块的时候喜欢拍";

WSChatModel *model3 = [[WSChatModel alloc]init];
model3.chatCellType=WSChatCellType_Text;
model3.isSender=1;
model3.content=@"进你空间不让俺进,就施舍我一张呗";

WSChatModel *model4 = [[WSChatModel alloc]init];
model4.chatCellType=WSChatCellType_Text;
model4.isSender=0;
model4.content=@"哈哈,好吧!";

WSChatModel *model5 = [[WSChatModel alloc]init];
model5.chatCellType=WSChatCellType_Image;
model5.isSender=0;
model5.content=@"red";

WSChatModel *model6 = [[WSChatModel alloc]init];
model6.chatCellType=WSChatCellType_Text;
model6.isSender=1;
model6.content=@"这个是你?";

WSChatModel *model7 = [[WSChatModel alloc]init];
model7.chatCellType=WSChatCellType_Text;
model7.content=@"比我想象中的还要漂亮!";
model7.isSender=1;


WSChatModel *model8 = [[WSChatModel alloc]init];
model8.chatCellType=WSChatCellType_Time;
model8.content=@"12-05 18:59";

WSChatModel *model9 = [[WSChatModel alloc]init];
model9.chatCellType=WSChatCellType_Text;
model9.isSender=1;
model9.content=@"你现在在干嘛呢?";

WSChatModel *model10 = [[WSChatModel alloc]init];
model10.chatCellType=WSChatCellType_Text;
model10.isSender=0;
model10.content=@"我现在在听~歌";

WSChatModel *model11 = [[WSChatModel alloc]init];
model11.chatCellType=WSChatCellType_Text;
model11.isSender=1;
model11.content=@"我不信,你来一张照片我就相信";

WSChatModel *model12 = [[WSChatModel alloc]init];
model12.chatCellType=WSChatCellType_Text;
model12.isSender=0;
model12.content=@"不来";

WSChatModel *model13 = [[WSChatModel alloc]init];
model13.chatCellType=WSChatCellType_Text;
model13.isSender=0;
model13.content=@"你昨天撤销了那张图片,我觉得好眼熟,可惜一点就没了";

WSChatModel *model14 = [[WSChatModel alloc]init];
model14.chatCellType=WSChatCellType_Image;
model14.isSender=0;
model14.content=@"yellow";

WSChatModel *model15 = [[WSChatModel alloc]init];
model15.chatCellType=WSChatCellType_Text;
model15.isSender=0;
model15.content=@"我说怎么这么眼熟呢,原来我们很像";

WSChatModel *model16 = [[WSChatModel alloc]init];
model16.chatCellType=WSChatCellType_Image;
model16.isSender=0;
model16.content=@"we";

WSChatModel *model17 = [[WSChatModel alloc]init];
model17.chatCellType=WSChatCellType_Text;
model17.isSender=0;
model17.content=@"不觉得~~~";


WSChatModel *model18 = [[WSChatModel alloc]init];
model18.chatCellType=WSChatCellType_Time;
model18.content=@"12-14 20:57";


WSChatModel *model19 = [[WSChatModel alloc]init];
model19.chatCellType=WSChatCellType_Text;
model19.isSender=0;
model19.content=@"你刚才打电话我不在";

WSChatModel *model20 = [[WSChatModel alloc]init];
model20.chatCellType=WSChatCellType_Text;
model20.isSender=0;
model20.content=@"我不在,我刚才洗澡呢";

WSChatModel *model21 = [[WSChatModel alloc]init];
model21.chatCellType=WSChatCellType_Text;
model21.isSender=0;
model21.content=@"我不在,我刚才洗澡呢";

WSChatModel *model22 = [[WSChatModel alloc]init];
model22.chatCellType=WSChatCellType_Audio;
model21.isSender=0;
WSChatModel *model23 = [[WSChatModel alloc]init];
model23.chatCellType=WSChatCellType_Audio;
model23.isSender=0;
WSChatModel *model24 = [[WSChatModel alloc]init];
model24.chatCellType=WSChatCellType_Audio;
model24.isSender=0;


WSChatModel *model25 = [[WSChatModel alloc]init];
model25.chatCellType=WSChatCellType_Text;
model25.isSender=1;
model25.content=@"我说怎么这么眼熟呢,原来我们很像";

WSChatModel *model26 = [[WSChatModel alloc]init];
model26.chatCellType=WSChatCellType_Image;
model26.isSender=1;
model26.content=@"ai";

WSChatModel *model27 = [[WSChatModel alloc]init];
model27.chatCellType=WSChatCellType_Text;
model27.isSender=0;
model27.content=@"你觉得我现在美吗?";

WSChatModel *model28 = [[WSChatModel alloc]init];
model28.chatCellType=WSChatCellType_Text;
model28.isSender=1;
model28.content=@"嗯?";

WSChatModel *model29 = [[WSChatModel alloc]init];
model29.chatCellType=WSChatCellType_Image;
model29.isSender=0;
model29.content=@"wash";

WSChatModel *model30 = [[WSChatModel alloc]init];
model30.chatCellType=WSChatCellType_Text;
model30.isSender=0;
model30.content=@"不许想入非非,不该看的别看!";

WSChatModel *model31 = [[WSChatModel alloc]init];
model31.chatCellType=WSChatCellType_Audio;
model31.isSender=0;
WSChatModel *model32 = [[WSChatModel alloc]init];
model32.chatCellType=WSChatCellType_Audio;
model32.isSender=0;

WSChatModel *model33 = [[WSChatModel alloc]init];
model33.chatCellType=WSChatCellType_Text;
model33.isSender=1;
model33.content=@"大晚上的好拼!";

WSChatModel *model34 = [[WSChatModel alloc]init];
model34.chatCellType=WSChatCellType_Text;
model34.isSender=0;
model34.content=@"哈哈!";

WSChatModel *model35 = [[WSChatModel alloc]init];
model35.chatCellType=WSChatCellType_Image;
model35.isSender=0;
model35.content=@"black";

WSChatModel *model36 = [[WSChatModel alloc]init];
model36.chatCellType=WSChatCellType_Text;
model36.isSender=1;
model36.content=@"这个晚上出门会吓到人的哦";

WSChatModel *model37 = [[WSChatModel alloc]init];
model37.chatCellType=WSChatCellType_Time;
model37.content=@"12-16 22:25";

WSChatModel *modela = [[WSChatModel alloc]init];
modela.chatCellType=WSChatCellType_Audio;
modela.isSender=1;
WSChatModel *modelb = [[WSChatModel alloc]init];
modelb.chatCellType=WSChatCellType_Audio;
modelb.isSender=1;
WSChatModel *modelc = [[WSChatModel alloc]init];
modelc.chatCellType=WSChatCellType_Audio;
modelc.isSender=1;


[_DataSource addObject:model1];
[_DataSource addObject:model2];
[_DataSource addObject:model3];
[_DataSource addObject:model4];
[_DataSource addObject:model5];
[_DataSource addObject:model22];
[_DataSource addObject:model23];
[_DataSource addObject:modela];
[_DataSource addObject:modelb];
[_DataSource addObject:modelc];
[_DataSource addObject:model24];
[_DataSource addObject:model6];
[_DataSource addObject:model7];
[_DataSource addObject:model8];


[_DataSource addObject:model9];
[_DataSource addObject:model10];
[_DataSource addObject:modela];
[_DataSource addObject:modelb];
[_DataSource addObject:modelc];
[_DataSource addObject:model11];
[_DataSource addObject:model22];
[_DataSource addObject:model23];
[_DataSource addObject:model24];
[_DataSource addObject:modela];
[_DataSource addObject:modelb];
[_DataSource addObject:modelc];
[_DataSource addObject:model12];
[_DataSource addObject:model13];
[_DataSource addObject:model14];
[_DataSource addObject:modela];
[_DataSource addObject:modelb];
[_DataSource addObject:modelc];
[_DataSource addObject:model15];
[_DataSource addObject:model16];
[_DataSource addObject:model17];
[_DataSource addObject:model18];

[_DataSource addObject:model19];
[_DataSource addObject:model20];
[_DataSource addObject:model21];
[_DataSource addObject:model22];
[_DataSource addObject:modela];
[_DataSource addObject:modelb];
[_DataSource addObject:modelc];
[_DataSource addObject:model23];
[_DataSource addObject:model24];
[_DataSource addObject:model25];
[_DataSource addObject:model26];
[_DataSource addObject:model27];
[_DataSource addObject:model28];
[_DataSource addObject:model29];
[_DataSource addObject:model30];
[_DataSource addObject:model22];
[_DataSource addObject:model23];
[_DataSource addObject:model24];
[_DataSource addObject:model31];
[_DataSource addObject:model32];
[_DataSource addObject:model33];
[_DataSource addObject:modela];
[_DataSource addObject:modelb];
[_DataSource addObject:modelc];
[_DataSource addObject:model34];
[_DataSource addObject:model35];
[_DataSource addObject:model36];
[_DataSource addObject:model37];





