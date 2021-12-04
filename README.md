单机单卡的运行方式：python HyperAttentionDTI_main.py

单机单线程多卡运行方式：python HyperAttentionDTI_main.py

单机多线程多卡运行方式： python -m torch.distributed.launch HyperAttentionDTI_main.py


单卡不用运行，我注释了3种运行方式（是否可以运行我不知道，我这边没有设备调试）：
1,单机单进程多卡gpu
2,单机多进程多卡gpu 
3,单机多进程多卡gpu

多gpu条件下，需要修改指定的gpu个数。
都在HyperAttentionDTI_main.py下，我用#-------------------------------------------------标注出来了。
