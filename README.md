# 官方权威地域数据 - Python 一键搞定

> 当前代码获取的是截止至 2019-12-31 的数据
>
> 地址为：http://www.stats.gov.cn/tjsj/tjbz/tjyqhdmhcxhfdm/2019/
>
> 代理地址采用的是西祠代理（似乎不能访问了）：https://www.xicidaili.com/nn/

```
// 最后获取的数据格式为 JSON
// 省份 / 城市 ... 区分开, 各自单独一个文件保存
{
    "110100000000":[
        {
            "code":"110101000000",
            "name":"东城区",
            "parent":"110100000000"
        }
    ]
    // ...
}

// 若要封装成其它数据，请自行修改（比如 MySQL 语句等）
```
