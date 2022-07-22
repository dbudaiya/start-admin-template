起手工作

开始编写模板,用于开发后台管理

技术选型(都是最新技术发布,慎重考虑用于生产)  
> 大部分还是应该考虑结合使用vuecli原生

vue3.x + vite3 + pinia +vue-router@next + unocss(练手可用于生产[库作者声明]) + vueuse + ElementUI(PC端) +VantUI(移动端) +  TypeScript + pnpm + ...

插件选型

期望  > 环境变量文件的加入 图表icon的标准配置

首屏优化:
组件UI库必须以按需导入的方式
图片考虑以雪碧图方式加载(https://www.toptal.com/developers/css/sprite-generator)
路由懒加载方式
考虑CDN节点引入依赖*(可)


可能遇到的问题:

预期

目前  vite插件可能在vuecli中不存在,得自行编写需要

缩短学习一个库的成本 粗略阅读一些常见热门的github仓库

Github
commit message standards
fix bug解决
chore 杂活
feat  新功能





正在做的事情

阅读github 

实践js方法模式

后续将会做的事情

算法仓库代码编写 => 视频? 自学