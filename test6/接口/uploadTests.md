# 接口：uploadTests  [返回](../README.md)
用例： [发布实验](../用例/发布实验.md)

- 权限：
     老师：可以看到RESULT_SUM，WEB_SUM。

- 功能：
    发布实验信息。

- API请求地址：
   接口基本地址/v1/api/uploadTests

- 请求方式 ：
    GET

- 请求实例：
    {
            "test_name":"实验4：图书管理系统顺序图绘制",
            "GitHub":"https://github.com/zwdbox/is_analysis/test4"
            }
- 请求参数说明：

  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|
  |test_name|实验名称|
  |GitHub|GitHub地址|

- 返回实例：

 {
                 "status": true,
                 "info":null

             }

- 返回参数说明：

  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|
  |status|bool类型，true表示正确的返回，false表示有错误|
  |info|结果说明信息|
