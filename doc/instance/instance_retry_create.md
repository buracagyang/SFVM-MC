# PUT /instance/recreate 虚拟机重新创建


## 请求参数
| 参数 | 是否必须 | 类型 | 描述 | 
|-----|----------|------|-------------|-------|
| request_ids   | 是| string| 虚拟机请求ID（可以多个，用逗号分隔）|

## 请求参数
```
{
    "request_ids": "req-958be5a8-90d3-5887-a950-5f0203374660,req-4486b344-2d14-f2fe-f651-3ee88b384164"
}
```

## 返回参数
```json

	{
	  "msg": "success",
	  "code": 0,
	  "data": {}
    }

```
