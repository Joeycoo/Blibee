## 关于Blibee


**Blibee：** 是一个基于Vue.js + iview 前端框架搭建的后台管理系统模板，适用于如：OA,CRM,CMS等管理系统的后台开发。 


### 布局和菜单

该模板以左菜单，右操作面板来布局。左侧菜单树目前支持两级菜单，菜单树以JSON格式定义。其中，菜单项支持指定图标，菜单的链接地址等选项，详细的配置属性如：
```
{
    title:"用户及授权",
    name:"1",
    icon:"logo-apple",
    menuItem:[
        {
            label:"用户管理",
            name:"1-1",
            href:"/account/user/list",
            icon:"logo-apple"
        },
        {
            label:"资源管理",
            name:"1-2",
            href:"/account/resource/list",
            icon:"logo-windows"
        },
        {
            label:"角色管理",
            name:"1-3",
            href:"/account/role/list",
            icon:"logo-tux"
        }
    ]
}
```

左侧菜单支持收起和展开，当菜处于收起状态时，只显示菜单项的图标，这样使得整个系统的在横向的操作界面空更宽一些，在数据的展示上效果会更好。 

### 选项卡

右侧操作区是以选项卡(iframe)打开的各个操作界面，每个选项卡页面均为一个独立的页面。

当点击每个选项卡时，左侧菜单会自动跟踪到当前打开的菜单上。

选项卡切换时，支持切换动画效果，视觉体验非常不错。 
