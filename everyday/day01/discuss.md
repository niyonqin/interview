# 项目中的rpc和http如何选择, 如果rpc比http通信要快, 原理是什么

## person 1
- 够不够用的问题，看规模
- 原理是协议，自定义的rpc能省掉很多开销
- 自定义协议就能减少废话，rpc其实就是我要访问你的什么方法，参数是什么

## person 2
- 我知道的一点是，http需要解析文本，rpc直接是字节对应结构体字段，解析更快
