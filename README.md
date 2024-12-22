# 📜custom-rules
Custom rules for myself, maybe not fit for you.  
Update frequency: anytime.  
## 🔗Links  
If you would like to use `CustomRules.yaml`, you can get it with following links:  
- Original: https://raw.githubusercontent.com/Paloexiz/custom-rules/main/Clash/CustomRules.yaml  
- CDN: https://fastly.jsdelivr.net/gh/Paloexiz/custom-rules@main/Clash/CustomRules.yaml  
## ℹ️Note
To use `CustomRules.yaml` file, your `behavior` property should be `classical`.  
### Example:  
```yaml
rule-providers:
  custom:
    {
      type: http,
      interval: 86400,
      format: mrs,
      behavior: classical,
      url: "https://fastly.jsdelivr.net/gh/Paloexiz/custom-rules@main/Clash/CustomRules.yaml",
      path: "./ruleset/paloexiz/customrules.yaml",
    }
```
