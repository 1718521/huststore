## zrem ##

**接口:** `/zrem`

**方法:** `GET | POST`

**参数:** 

*  **tb** （必选）  
*  **key** （必选）  
*  **ver** （可选）

该接口是 `/hustdb/zrem` 的代理接口，参数详情可参考 [这里](../hustdb/hustdb/zrem.md) 。

**使用范例:**

    curl -i -X POST "http://localhost:8082/zrem?tb=test_table" -d "test_key"

[上一页](../ha.md)

[回首页](../../index.md)