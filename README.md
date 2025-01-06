<div align="center">
<h1>AdGuard Rule</h1>
  <p>
    一个简易的Java程序，用于合并与更新 AdGuard 过滤规则
</p>
</div>


<h2 id="a">📔 说明</h2>

本项目旨在按需求整合 `AdGuard` 规则。定时从上游订阅获取规则，去除`重复`和`不受支持`的规则并进行分类。如果存在误杀请手动放行。  
支持`AdGuard`、`AdGuard Home`,每`12小时`自动更新一次   


#### 本地规则

- [mylist](#)
> 主要是对上游规则的修正补充，根据日常使用体验，解除一些失误拦截

<h2 id="b">🎯 订阅</h2>

| 名称           | 说明                                                | Github订阅                                                                              | jsDelivr加速订阅                                                                        |
|--------------|---------------------------------------------------|---------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------|
| `all.txt`    | 去重的规则合集，包含以下所有规则，适用于 `AdGuard` 客户端                | [✈️点此查看](https://raw.githubusercontent.com/dalamudx/AdGuard-Rule/release/rule/all.txt)      | [🚀点此查看(延迟)](https://cdn.jsdelivr.net/gh/dalamudx/AdGuard-Rule@release/rule/all.txt)    |
| `adgh.txt`   | 针对 `AdGuardHome` 的规则，包含 `domain.txt` `regex.txt`和`mylist.txt` | [✈️点此查看](https://raw.githubusercontent.com/dalamudx/AdGuard-Rule/release/rule/adgh.txt)   | [🚀点此查看(延迟)](https://cdn.jsdelivr.net/gh/dalamudx/AdGuard-Rule@release/rule/adgh.txt)   |
| `domain.txt` | 域名规则，`AdGuard`和`AdGuardHome`都支持                                       | [✈️点此查看](https://raw.githubusercontent.com/dalamudx/AdGuard-Rule/release/rule/domain.txt) | [🚀点此查看(延迟)](https://cdn.jsdelivr.net/gh/dalamudx/AdGuard-Rule@release/rule/domain.txt) |
| `hosts.txt`  | `hosts` 规则，~~包含一些访问加速~~                           | [✈️点此查看](https://raw.githubusercontent.com/dalamudx/AdGuard-Rule/release/rule/hosts.txt)  | [🚀点此查看(延迟)](https://cdn.jsdelivr.net/gh/dalamudx/AdGuard-Rule@release/rule/hosts.txt)  |
| `modify.txt` | 修饰规则，`AdGuard`支持                                      | [✈️点此查看](https://raw.githubusercontent.com/dalamudx/AdGuard-Rule/release/rule/modify.txt) | [🚀点此查看(延迟)](https://cdn.jsdelivr.net/gh/dalamudx/AdGuard-Rule@release/rule/modify.txt) |
| `regex.txt` | 正则规则，`AdGuardHome`支持                                       | [✈️点此查看](https://raw.githubusercontent.com/dalamudx/AdGuard-Rule/release/rule/regex.txt) | [🚀点此查看(延迟)](https://cdn.jsdelivr.net/gh/dalamudx/AdGuard-Rule@release/rule/regex.txt) |
| `mylist.txt` | 自用补充规则，人工更新                                       | [✈️点此查看](https://raw.githubusercontent.com/dalamudx/AdGuard-Rule/release/rule/mylist.txt) | [🚀点此查看(延迟)](https://cdn.jsdelivr.net/gh/dalamudx/AdGuard-Rule@release/rule/mylist.txt) |
