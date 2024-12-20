# aizhanCheckBr
快速查询爱站百度权重，从此告别手动查询的苦恼

# 使用方式
1. 保存需要查询的url文件，格式为：
~~~
http://www.baidu.com
https://www.baidu.com
www.baidu.com
baidu.com
~~~
以上均可，程序会自动提取根域名进行权重查询
2. 使用工具进行查询
~~~
aizhanCheckBr.exe -f urls.txt
~~~
![image](https://github.com/user-attachments/assets/7fd2c2ab-e986-424f-b549-aa4be2fdfe28)
程序会自动保存查询结果至`爱站移动权重.txt`，为了便于区分权重大于1的将保存至`爱站移动权重大于1.txt`中
