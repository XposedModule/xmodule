# 如何在Xmodule发布插件
你只能在此项目中提交issues方式发布插件，格式必须为以下形式：
  ```
 package: 包名
 
 apk_name: 插件名称
 
 apk_ver: 插件版本
 
 apk_author: 插件作者
 
 apk_source: 是否开源（不开源填 否；开源填写开源地址）
 
 apk_down_url: 插件下载地址
```

# Xmodule发布机制

1. 当您提交到issues后，XMODULE爬虫将会通过github接口取回issues数据
2. 取回数据后，数据存入副库并进入待审核列表
3. 公测人员(部分用户)取得副库数据后进行试用，超过>10人赞成通过后，同步到主库
4. 此周期为3~6天
