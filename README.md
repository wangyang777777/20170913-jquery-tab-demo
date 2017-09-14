# 20170913-jquery-tab-demo

这是一个扩展在jQuery上的tab类插件,用面向对象方式开发.

可配置一下工作方式:

config = {
//        用来定义鼠标的触发类型，是click还是mouseover
            "triggerType": "click",
//        用来定义内容切换效果，是直接切换，还是淡入淡出的效果
            "effect": "fade",
//        默认展示第几个tab
            "invoke": 1,
//        用来定义tab的自动切换，当指定了事件间隔，就表示自动切换，并且切换时间为指定的时间间隔
            "auto": false
        }