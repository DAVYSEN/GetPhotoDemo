# GetPhotoDemo
最近做了几个商城,发现个人中心那,头像修改都是统一一种模式,调取系统摄像头和相册上传头像.就写个总结,以后就直接拿来用,顺便总结遇到的问题.

 1. 6.0之后敏感权限动态申请
 2. 7.0之后 使用本地真实的Uri路径不安全,直接使用Uri.fromFile(file);会报FileUriExposedException异常