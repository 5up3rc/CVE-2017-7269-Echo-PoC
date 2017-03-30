
### CVE-2017-7269 远程代码执行回显验证

---
我们团队对此次 CVE-2017-7269 漏洞的分析报告: https://ht-sec.org/cve-2017-7269-vulnerabilities/

默认PoC 只能弹`calc.exe` ,现在修改成可以响应请求,命令格式为:<br/>

CVE-2017-7269_remote_echo.py ip_address port

<br/>

效果如下:<br/>

![](https://raw.githubusercontent.com/lcatro/CVE-2017-7269-Echo-PoC/master/example.png)
