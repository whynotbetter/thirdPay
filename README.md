# thirdPay
与第三方支付有关的一些模块功能，主要是支付宝和微信支付。
整理自前面做过的项目，去掉了具体的细节。
其实这几年，兴起的BaaS（后端即服务：Backend as a Service）服务就是把一些公用的、通用的后端业务封装成后端的边界服务，提供给移动应用开发者，它们都旨在帮助移动开发者解决后端服务问题，进而让开发移动应用变得更加容易。


这个项目是用maven构建的，其中引用了core、third.mybatis这两个项目，所以如果单独打开这个项目，会报错。如果需要用到别的项目去，需要把core、third.mybatis这两个项目也一起加进去
