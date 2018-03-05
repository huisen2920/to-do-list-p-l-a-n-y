# to-do-list-p-l-a-n-y

goal:
  1.pomelo
  2.mongodb
  3.express
  
  

cocos的图层一定要管理好， 最好不要UI编辑器和代码混合 addChild, 或者先在UI编辑器中设置好图层，然后将不同的元素根据不同的需求，添加到不同的图层进行显示， 如果乱使用 addChild 会导致图层混乱。 最终导致元素显示图层不正确。


游戏服务端开发关键点:
  1.多线程和进程,以及集群或者分布式的进程间的管理和使用
  2.高效的网络通信 (libev , libuv , libevent)
  3.服务器和客户端通信数据的编码和解码, 以及加密解密. protobuf
  4.业务逻辑的脚本化:lua , python等
