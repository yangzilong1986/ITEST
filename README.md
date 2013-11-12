ITEST
=====

ITEST是面向主要的service接口诸如：HTTP，SOAP，JSON-RPC的轻量级自动化测试框架。将参数的输入、请求执行、结果解析、数据验证、数据准备与清理各个环节都做了封装，以数据文本文件为接口，降低自动化测试过程中case书写的难度。

数据驱动测试执行是该框架的主要特征，都体现在case“文件”中：
1. 测试输入：接口测试需要输入的参数
2. 数据验证：response的预期字符串，或者验证mysql数据的sql语句
3. 数据准备与清理：构造测试数据的sql，或者service接口

底层主要使用的是HttpClient+JUnit

-----
