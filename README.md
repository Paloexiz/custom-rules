# 📜custom-rules  
🌐Select your Language: English | [简体中文](README_CN.md)  
  
Custom rules for myself, maybe not fit for you.  
Update frequency: anytime.  
## 🔗Links  
##### 📜If you would like to use `CustomRules.yaml`, you can get it with following links:  
- Original: [View or Download](https://raw.githubusercontent.com/Paloexiz/custom-rules/main/Clash/CustomRules.yaml)  
- CDN(maybe 24-hour-delaying sync): [View or Download](https://fastly.jsdelivr.net/gh/Paloexiz/custom-rules@main/Clash/CustomRules.yaml)  
##### 🌏Break region restriction? You can use `BlockedDomains.yaml` by following links:  
- Original: [View or Download](https://raw.githubusercontent.com/Paloexiz/custom-rules/main/Common/Unlock/Clash/BlockedDomains.yaml)  
- CDN(maybe 24-hour-delaying sync): [View or Download](https://fastly.jsdelivr.net/gh/Paloexiz/custom-rules@main/Common/Unlock/Clash/BlockedDomains.yaml)  
##### ⛓️‍💥Boost slow connections? You can use `SlowDomains.yaml` by following links:  
- Original: [View or Download](https://raw.githubusercontent.com/Paloexiz/custom-rules/main/Common/Boost/Clash/SlowDomains.yaml)  
- CDN(maybe 24-hour-delaying sync): [View or Download](https://fastly.jsdelivr.net/gh/Paloexiz/custom-rules@main/Common/Boost/Clash/SlowDomains.yaml)  
## ℹ️Note  
To use above files, your `behavior` property should be `classical`.  
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
