## demo_tools
基于现有框架进行开发，完成了授课工具：
- 形状
- 板中板
- 计时器
- 尺规

1. 较多用到了定位，偏移，旋转。  
2. 形状绘制采用svg，鼠标在四个象限移动时，根据形成的矩形，实时计算svg的path  
3. 尺规画线采用canvas，同时为了避免交互冲突，动态绘制的过程是在额外的预览层完成。  

![image](./gif/demo_tool.gif)