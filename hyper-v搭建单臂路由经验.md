# 总结

部署的主要指导在这个链接 [link](https://github.com/smartOturtle/books/blob/master/Hyper-V%20%E9%83%A8%E7%BD%B2%20OpenWRT%20%E8%BD%AF%E8%B7%AF%E7%94%B1.pdf)

有几点需要特别注意

1. 先添加内部网络，再添加外部网络。
2. 删除除了 lan 口之外的所有 wan 口
3. 要在设备管理器中把网桥的中的 large segment offload 关掉，不然上传的性能会受到极大的影响。
