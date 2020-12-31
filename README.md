# Poc-Exp
记录在漏洞研究过程中编写的 PoC/Exp
```shell
# Poc框架
pocsuite3
```


## Citrix
- 🎯 cve-2020-8209(Citrix XenMobile 目录遍历/任意文件读取漏洞)

## Confluence
- 🎯 cve-2019-3396(Atlassian Confluence 路径穿越漏洞)

## Eyou(亿邮)
- 🎯 wooyun-2013-028987
- 🎯 wooyun-2014-056245
- 🎯 wooyun-2014-058301(亿邮 命令执行漏洞-storage_explore.php)
- 🎯 wooyun-2014-061538(亿邮 敏感信息泄漏漏洞-sysinfo.html)
- 🎯 wooyun-2014-070551
- 🎯 wooyun-2014-072314(亿邮 SQL注入漏洞-print_addfeelog.php)
- 🎯 wooyun-2015-0101419
- 🎯 wooyun-2015-0135406

## Jboss
- 🎯 cve-2006-5750
- 🎯 cve-2007-1036
- 🎯 cve-2010-0738
- 🎯 [cve-2010-1871(JBoss Seam Framework远程代码执行漏洞)](http://blog.o0o.nu/2010/07/cve-2010-1871-jboss-seam-framework.html)
- 🎯 cve-2015-7501
- 🎯 cve-2013-4810
- 🎯 [cve-2017-7504(JBoss 4.x JBossMQ JMS 反序列化漏洞)](https://github.com/vulhub/vulhub/tree/master/jboss/CVE-2017-7504)
- 🎯 [cve-2017-12149(JBOSS AS 5.x/6.x反序列化命令执行漏洞)](https://github.com/vulhub/vulhub/tree/master/jboss/CVE-2017-12149)
- 🎯 cve-xxxx-xxxxx(JBoss jmx-consoleHtmlAdaptor addURL() 文件上传漏洞)

## Phpstudy
- 🎯 [phpstudy backdoor](https://xz.aliyun.com/t/6423)

## Resin
- 🎯 cve-2006-1953(Resin Windows 目录遍历漏洞-/C:%5C/)
- 🎯 cve-2006-2437(Resin 任意文件读取漏洞-viewfile)
- 🎯 cnnvd-200705-315(Resin Windows %20 目录遍历漏洞-/%20../web-inf/)
- 🎯 cve-xxx-xxxx(Resin 任意文件读取漏洞-inputFile)
- 🎯  cve-xxx-xxxx(Resin SSRF漏洞-inputFile)

## Spring
- 🎯 [cve-xxxx-xxxx(SpringBoot Actuator未授权访问漏洞)](https://xz.aliyun.com/t/2233)
- 🎯 cve-2018-1271(Spring MVC目录穿越/遍历漏洞) 
- 🎯 cve-2019-3799(Spring Cloud Config Server 路径穿越/任意文件读取漏洞)
- 🎯 cve-2020-5405(Spring Cloud Config Server路径遍历漏洞)
- 🎯 cve-2020-5410(Spring Cloud Config目录穿越/遍历漏洞)

## Thinkadmin
- 🎯 cve-2020-25540(thinkadmin 目录遍历/任意文件读取漏洞)
- 🎯 cnvd-2020-33163

## Weaver(泛微)

- 🎯 [wooyun-2016-0191882(泛微OA SQL注入漏洞-HrmResourceContactEdit.jsp)](http://wy.zone.ci/bug_detail.php?wybug_id=wooyun-2016-0191882)
- 🎯 [wooyun-2016-0178866(泛微OA 某接口任意SQL命令执行漏洞)](https://www.uedbox.com/post/13103/)
- 🎯 [wooyun-2016-0169872(泛微OA 任意文件遍历&操作漏洞)](https://www.onebug.org/wooyundata/72008.html)
- 🎯 [wooyun-2016-0198158(泛微OA SQL注入漏洞)](https://www.onebug.org/wooyundata/74197.html)
- 🎯 [wooyun-2016-0198158(泛微OA 任意文件读取漏洞)](https://www.onebug.org/wooyundata/74197.html)
- 🎯 [wooyun-2016-0169453(泛微OA SOAP注入漏洞)](https://www.uedbox.com/post/14232/)
- 🎯 [wooyun-2016-0215533(泛微OA 数据库任意操作漏洞-xp_cmdshell)](http://wy.zone.ci/bug_detail.php?wybug_id=wooyun-2016-0215533)
- 🎯 cnvd-2017-03561(泛微e-mobile login.do表达式注入漏洞)
- 🎯 cnvd-2019-29900(泛微OA 任意文件下载漏洞)
- 🎯 cnvd-2019-29902(泛微OA 任意文件读取漏洞)
- 🎯 cnvd-2019-32204(泛微OA 远程命令执行漏洞)
- 🎯 cnvd-2019-34241(泛微OA 前台SQL注入漏洞-WorkflowCenterTreeData.jsp)
- 🎯 cnvd-2019-40989(泛微OA SQL注入漏洞-SyncUserInfo.jsp)
- 🎯 cnvd-2019-40989(泛微OA SQL注入漏洞-WorkflowCenterTreeData.jsp)
- 🎯 cnvd-2019-41610(泛微OA SQL注入漏洞-validate.jsp)
- 🎯 cnvd-2020-59520(泛微e-bridge 目录遍历/任意文件读取漏洞)
- 🎯 cnvd-xxxx-xxxxx(泛微OA 数据库配置信息泄露漏洞-DBconfigReader.jsp)

## Webmin
- 🎯 [cve-2018-8712(Webmin 任意文件读取漏洞)](https://www.7elements.co.uk/resources/technical-advisories/webmin-1-840-1-880-unrestricted-access-arbitrary-files-using-local-file-include/)
- 🎯 [cve-2019-15107(Webmin 命令执行漏洞)](https://github.com/jas502n/CVE-2019-15107)
- 🎯 cve-2020-35606(Webmin 命令执行漏洞)

## Yonyou(用友)
- 🎯 cnvd-2020-49261(用友GRP-U8 XXE漏洞-xp_cmdshell)

