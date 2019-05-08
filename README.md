### 更新

原AppCrawler只支持1.8版本，替换java-client:7.0之后，可以
支持到最新版本的appium

### 打包

```shell
mvn assembly:assembly
```

### 测试

```shell
java -jar target/appcrawler-2.4.0-jar-with-dependencies.jar -a ApiDemos-debug.apk
```
