阿里云计算开放服务软件开发工具包Java版
Aliyun OSS SDK for Java

版权所有 （C）阿里云计算有限公司

Copyright (C) Alibaba Cloud Computing
All rights reserved.

http://www.aliyun.com

环境要求：
- J2SE Development Kit (JDK) 6.0或以上版
- Apache Commons （Codec、HTTP Client和Logging）、JDOM等第三方软件包（已包含在SDK的下载压缩包中）。
- 必须注册有Aliyun.com用户账户，并开通OSS服务。


2.0.6更新日志：
1）添加setObjectAcl/getObjectAcl接口，用于设置、获取指定Object的ACL；
2）添加ClientConfiguration.setLogLevel接口设置全局日志级别，默认将404错误码日志级别设置为INFO；
3）添加ClientConfiguration.setSLDEnabled接口设置是否开启二级域名的访问方式；
4）添加ClientConfiguration.setSupportCname接口设置是否支持Cname作为Endpoint；
5）输出Invalid Response详细错误信息、完善OssException/ClientException错误信息；
6）修复设置Bucket默认ACL为private的bug；
7）修复upload part支持chunked编码的bug，并将输入流包装为可重试输入流；
8）添加webp至mime types列表。


TODO:
根据Objectkey获取URL


https://github.com/JiongboZhu/ucaruhome-oss-integration.git
https://github.com/JiongboZhu/ucaruhome-hchh.git

