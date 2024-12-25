# 📜自定义规则  
🌐语言选择：[English](README.md)  | 简体中文  
  
这是私人定制的自定义规则，可能并不适用于您的需求。  
更新频率：任何时候。  
## 🔗链接  
如需将`CustomRules.yaml`文件缓存于本地存储，您可以使用如下链接：  
- 原链接：   https://raw.githubusercontent.com/Paloexiz/custom-rules/main/Clash/CustomRules.yaml  
- 内容分发网络（可能会有24小时的延迟）：   https://fastly.jsdelivr.net/gh/Paloexiz/custom-rules@main/Clash/CustomRules.yaml  
## ℹ️注意事项  
如果想要使用`CustomRules.yaml`文件, 您的`behavior`属性应为`classical`项。  
### 示例:  
```yaml
rule-providers:
  custom:
    {
      type: http,
      interval: 86400,
      format: yaml,
      behavior: classical,
      url: "https://fastly.jsdelivr.net/gh/Paloexiz/custom-rules@main/Clash/CustomRules.yaml",
      path: "./ruleset/paloexiz/customrules.yaml",
    }
```
