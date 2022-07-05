UCMS_v1.6.0 任意文件上传漏洞

漏洞类型：

V 1.6.0
复现环境：

Windows 10
phpstudy

漏洞描述：
漏洞在/ucms-v1.6/ucms/sadmin/file.php文件中,对上的文件后缀没有做验证，导致可以上传任意文件

漏洞复现：
![image](https://user-images.githubusercontent.com/77734048/177239815-fa3be53f-a4d8-45e1-9548-0e3a6f37c471.png)
![image](https://user-images.githubusercontent.com/77734048/177240661-2b352dc3-0818-4ae6-94e4-26bf5b6fd752.png)
![image](https://user-images.githubusercontent.com/77734048/177240682-ae11ddca-61d5-49a8-b92f-5caf943d0cb8.png)
![image](https://user-images.githubusercontent.com/77734048/177240716-193fc2cf-bf75-4a38-910b-5dc6b65d7f33.png)



