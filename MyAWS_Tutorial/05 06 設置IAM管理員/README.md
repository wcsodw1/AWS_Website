# AWS_Website 設置IAM(建子管理員)
+ AWS_Website_Development

## 知識點 : 
+ 避免使用超級管理員Root根帳號, 應該分配適當有權帳號進行工作管理 最高權限!!(可刪除自己帳號的權利)

## 區別用戶 : 建議平常沒事不要使用根管理員!!

### Root 根帳號的使用時間通常只會在這些時候 : 
+ 控制其他管理帳號時(最高管理員(執行長)分權給其他管理員(職員)的概念)
+ 帳號契約解封時(ex : 與Amazon簽某些協議)
+ 帳號付款時(需要統一付款時)

### 普通管理員 : 平常工作時使用這個就可以了!!
+ 管理一般用戶(User, Group, Role)
+ 管理AWS資源(EC2, RDB)

### 普通成員 : 先建立子帳號, 讓子管理者使用的子帳號
+ AWS 資源使用 

### 實戰演習 : 

### IAM(Identity and Access Management) : 負責管理所有系統中的user 角色 權限 策略
1.簡化用戶登陸URL - wcsodw1<br>
2.建立管理員組 - wcsodw1-group<br>
3.建立普通管理員 - wcsodw1<br>

A.簡化用戶 : 
[IAM](https://208712304720.signin.aws.amazon.com/console)

B.建立管理員組 : <BR>
+ STEP1.勾選受管管理員權限

+ STEP2.創建了一個群組, 當未來創建一個使用者(STEP c)到這個組的時候,
              此用戶就具備了基本管理員的權限(開服務器, 做數據庫, 建立其他使用者(用戶), 建立角色)

+ STEP3.建立普通管理員 IAM
