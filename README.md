# DxMaven
一个用于远程依赖的代码仓库

#RxJava+Retrofit封装sdk
在Androidstudio开发的项目中使用：
1、project目录下的build.gradle
  allprojects {
    repositories {
        jcenter()
        maven{
            url "https://raw.github.com/DuanXun/DxMaven/snapshot/"
        }
    }
}

2、module或者app目录下build.gradle
dependencies {
    ...
    compile 'com.dx.rxjava_retrofit_http:rx_re_http:1.0.0-SNAPSHOT'
}
