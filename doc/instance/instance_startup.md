# PUT /instance/startup 虚拟机开机


## 请求参数
| 参数 | 是否必须 | 类型 | 描述 | 
|-----|----------|------|-------------|-------|
| instance_ids   | 是| string| 虚拟机ID（可以多个，用逗号分隔）|

## 请求参数
```
{
    "instance_ids": "1,2,3,4"
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
