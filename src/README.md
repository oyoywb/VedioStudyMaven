# VedioStudyMaven
视频学习网站。采用原生JSP+Servlet，相关技术：单点登录、图形验证码、文件上传、视频转码、视频记忆播放或者断点播放。

一、使用
导入项目后，将项目设置为Javaweb，并使用maven管理即可。视频以及图片资源放在webapp目录下，构建相应的数据库即可使用。

二、功能
使用原生的JSP+Servlet，后期为了项目提升会加入相应的ajax。该网站提供了图形验证码登录，不支持多地登录，在管理员模式下支持视频图片资源的上传和转码，实现了用户在离开视频后，再次进入会跳转到相应播放位置的功能，也就是记忆播放。