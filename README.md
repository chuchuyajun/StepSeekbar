# StepSeekbar
类似步骤选择器的seekbar

##非常简单,如图:
![image](https://github.com/phyooos/StepSeekbar/blob/master/img/stepseekbar.gif)

----
##没有提供代码修改参数的功能,暂时只能通过在xml中配置
```
    <declare-styleable name="StepSeekbar">
        <!--seekbar自身高度-->
        <attr name="seekbarHeight" format="dimension" />
        <attr name="textSize" format="dimension" />
        <!--文字与seekbar间距-->
        <attr name="spaceBetween" format="dimension" />
        <!--游标按钮(如果用shape,请设置高度宽度)-->
        <attr name="cursorBackground" format="reference" />
        <!--要设置的文字-->
        <attr name="markTextArray" format="reference" />
        <attr name="textColorNormal" format="color" />
        <attr name="textColorSelected" format="color" />
        <attr name="seekbarColorNormal" format="color" />
        <attr name="seekbarColorSelected" format="color" />
        <attr name="autoMoveDuration" format="integer" />
    </declare-styleable>
```

