# singbox mihomo rule

在singbox/mihomo.txt添加规则集，自动生成 singbox:srs/mihomo:mrs Format。fork后自己添加想要转换的规则集。

仓库 Settings ----> Actions ----> General ----> Workflow permissions ----> Read and write permissions 勾选上

规则集源文件写法eg:

```json
{
  "tag": "adblock",
  "type": "remote",
  "format": "binary",
  "url": "https://cdn.jsdelivr.net/gh/77160860/rule@main/singbox/adblock.srs",
  "download_detour": "DIRECT"
}
```
```json
{
  "tag": "filter",
  "type": "remote",
  "format": "source",
  "url": "https://cdn.jsdelivr.net/gh/77160860/rule@main/singbox/filter.json",
  "download_detour": "DIRECT"
}
```
