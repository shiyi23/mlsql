# 多租户

MLSQL Engine 实例支持多租户。默认是关闭的，需要通过http请求参数开启。
多租户一旦开启后，主要有：

1. 共享MLSQL Engine所有计算资源
2. 临时表互相不可见
3. 每个登录用户都有自己主目录
4. 自己创建的UDF 函数互不可见