# QT-IMC
 使用C/C++语言和QT库开发的一个即时通讯类Demo（大二练手项目）
 * 主要功能
   * 登录注册
   * 添加好友
   * 传输文件
 * 重点概述
   * TCP网络接口的封装和中介者模式（带有UDP封装但没有写入）
   * 传统网络的自定义协议封装
   * 熟悉CS的设计流程
### 客户端
 使用QT5.12 MINGW32bit工具链, socket使用WindowsAPI
### 服务端
 使用C/C++开发，socket也用的WindowsAPI
### 优化
  暂时能想到并且可以实现的优化
  * 传输文件的文件指纹可以用MD5实现
  * socket可以用QT库中的，提高跨平台性
  * 服务端可以使用epoll+线程池提高监听性和并发量
