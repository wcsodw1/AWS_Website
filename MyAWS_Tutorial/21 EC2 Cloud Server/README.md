#  AWS 建立EC2實例 : 開啟雲端服務之旅
AWS_Website_Development
==============================

## 知識點 : 
+ 1.建立一個通往可訪問的EC2服務器實例

(!!!)解釋 : 建立服務器之前, 必須要擁有一個謹慎且有系統性的服務器規劃, 比如說10~100做甚麼用 且只處理甚麼, 101-200做甚麼之類。(ex:172.16.10.10))


## 實戰演習 :
+ 示意圖 :
![image](./img/Ch21_EC2.png)


### Table :
+ 1.Amazon Linux 2 AMI
+ 2.t2.micro(新帳號12個月免費使用)
+ 3.chp12/13_IDC-vpc
+ 4.chp??-web-1a(!!!!)(公有網路chp15-vpc_subnet_public_web-1a step3 無法設置->改用私網可行...?!)
+ 5.自動分配公有IP
+ 6.內網IP:172.16.10.10/32
+ 7.Step5 服務器名稱(!!!) Name : DavidAmazon_Windows_Server-web-1a
+ 8.密鑰(!!!):DavidAmazon_Windows_Server-ssh-key

(!)
### SSH連接 : 

ˋˋˋbash
$ cp ~/Downloads/DavidAmazon_Server
$ chmod 400 DavidAmazon_Server-ssh-key.pem