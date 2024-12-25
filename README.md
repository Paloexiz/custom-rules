# 📜custom-rules  
🌐Select your Language: English | [简体中文](README_CN.md)  
  
Custom rules for myself, maybe not fit for you.  
Update frequency: anytime.  
## 🔗Links  
If you would like to use `CustomRules.yaml`, you can get it with following links:  
- Original: https://raw.githubusercontent.com/Paloexiz/custom-rules/main/Clash/CustomRules.yaml  
- CDN(maybe 24-hour-delaying sync): https://fastly.jsdelivr.net/gh/Paloexiz/custom-rules@main/Clash/CustomRules.yaml  
## ℹ️Note
To use `CustomRules.yaml` file, your `behavior` property should be `classical`.  
### Example:  
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
