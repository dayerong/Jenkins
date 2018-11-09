#### **Jenkins 持续部署**

``` 
            push                  pull                 rsync 
开发人员   --------->  gitlab  <---------  Jenkins   --------->  生产环境 

流程： 
1、开发人员push代码到Gitlab后，提代码发布申请至运维人员。 
2、申请批准后，运维人员通过微信发起自动发布。 
3、发布完成，微信通知运维人员，邮件通知开发人员。
```

- 通过结合企业号微信，运维人员可以用手机进行代码发布。


- 相关配置示例如下：

![image](https://github.com/dayerong/Jenkins/blob/master/screenshots/liucheng.png?raw=true)

![image](https://github.com/dayerong/Jenkins/blob/master/screenshots/deploy.png?raw=true)

![image](https://github.com/dayerong/Jenkins/blob/master/screenshots/rollback.png?raw=true)

![image](https://github.com/dayerong/Jenkins/blob/master/screenshots/general_1.png?raw=true)

![image](https://github.com/dayerong/Jenkins/blob/master/screenshots/general_2.png?raw=true)

![image](https://github.com/dayerong/Jenkins/blob/master/screenshots/general_3.png?raw=true)

![image](https://github.com/dayerong/Jenkins/blob/master/screenshots/%E6%BA%90%E7%A0%81%E7%AE%A1%E7%90%86_1.png?raw=true)

![image](https://github.com/dayerong/Jenkins/blob/master/screenshots/%E6%9E%84%E5%BB%BA%E7%8E%AF%E5%A2%83_1.png?raw=true)

![image](https://github.com/dayerong/Jenkins/blob/master/screenshots/%E6%9E%84%E5%BB%BA_1.png?raw=true)

![image](https://github.com/dayerong/Jenkins/blob/master/screenshots/%E6%9E%84%E5%BB%BA_2.png?raw=true)

![image](https://github.com/dayerong/Jenkins/blob/master/screenshots/%E6%9E%84%E5%BB%BA%E5%90%8E%E6%93%8D%E4%BD%9C.png?raw=true)