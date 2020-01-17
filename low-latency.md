# 低延迟系统相关笔记

## 线程亲和 (Thred Affinity)
线程亲和性能够强制使应用的线程运行在特定的一个或多个cpu上。通过这种方式，可以消除操作系统进行调度过程导致线程迁移所造成的影响。
> 一个开源的库 https://github.com/OpenHFT/Java-Thread-Affinity