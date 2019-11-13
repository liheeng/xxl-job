本项目对为xxl-job中xxl-job-admin的系统配置做了增强，使用Apollo配置中心，把application.properties里所有配置放到apollo配置中心，这样xxl-job-admin在不同的环境部署时，只需要修改配置中心的配置即可。

使用方法：
设置系统环境变量apollo.meta，xxl-job-admin启动时，会自动找到apollo配置中心并拉去配置。
例如：apollo.meta=http://10.5.52.94:8080


## xxl-job官方项目请参考
https://github.com/xuxueli/xxl-job
