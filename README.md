# AngularJS
##MVC框架：
####MVC（model  view  controller）紧密耦合结构
####由于ng-init定义数据模型是直接在view视图<html>标签中定义，所以违反了MVC模块之间要低耦合分离的设计原则，因此不推荐使用。
####使用controller控制器创建Model数据--符合MVC设计原则。
##MVVM：架构的前端框架
####VM：view model  视图模型（$scope）
####松散耦合结构：降低了各模块之间的耦合程度，高内聚低耦合，各模块之间更灵活、更独立，互不影响。
##AngularJS：
####在编写js代码时不再将精力放在DOM对象的操作上，而是聚焦在数据的组织和绑定，以及控制器代码的业务逻辑编写上，实现了数据的双向绑定。
###依赖注入：
####一般使用AngularJS快速构建CRUD（create read update delete）操作的SPA（single page application）应用。
