修改hudson.model.UpdateCenter.xml文件
```xml
<?xml version='1.1' encoding='UTF-8'?>
<sites>
  <site>
    <id>default</id>
    <url>https://mirrors.tuna.tsinghua.edu.cn/jenkins/updates/update-center.json</url>
  </site>
  <site>
    <id>active</id>
    <url>http://updates.jenkins-ci.org/update-center.json</url>
  </site>
</sites>
```
