# 基于阿里云AI Earth进行两广地区的野火易发性分析

什么是[阿里云AI Earth](https://engine-aiearth.aliyun.com/)?

# 安装SDK

```PowerShell
python -m pip install -U "aie-sdk[engine]"
```

AI Earth Engine 是 AI Earth地球科学云平台 开发者模式的客户端client，可以通过AI Earth Engine 函数进行云端计算。 sdk的计算模式是client-server模式，而不是一个本地运行的库，代码编写可以在本地， **数据和计算是在云端进行的** 。如果需要处理本地的数据，需要先将数据上云，然后通过aie-sdk调用平台云端计算功能进行数据处理并导出处理结果，最后通过平台下载处理结果。

# 注册阿里云账号

[阿里云·云小站](https://www.aliyun.com/minisite/goods?userCode=9k9dfqvv)

# 获取token
AI Earth 鉴权及初始化[文档](https://engine-aiearth.aliyun.com/docs/page/api?d=07f36f#heading-21:~:text=%E7%BC%96%E5%86%99%E4%BB%A3%E7%A0%81-,%E9%89%B4%E6%9D%83%E5%8F%8A%E5%88%9D%E5%A7%8B%E5%8C%96,-%E6%82%A8%E5%8F%AF%E4%BB%A5%E5%9F%BA%E4%BA%8E)

# 说明
有关本项目的具体介绍请移步我的[博客](https://blog.natsuu.top/2024/03/30/%EF%BC%88%E9%81%A5%E6%84%9F%EF%BC%89%E5%88%A9%E7%94%A8%E9%98%BF%E9%87%8C%E4%BA%91AI%20Earth%E8%BF%9B%E8%A1%8C%E9%87%8E%E7%81%AB%E9%A3%8E%E9%99%A9%E6%80%A7%E5%88%86%E6%9E%90/)