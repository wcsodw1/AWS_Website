
# AWS 職涯學習架構

## 基礎必備知識 : 
1.Linux 基礎
2.系統架構(node.js/ Python/ Golong)
3.網路基礎知識(TCP/IP, PORT, HTTP/HTTPS, SSH/SCP, Network, etc.)
4.數據庫基礎知識(RDB, SQL, NOSQL, etc., MongoDB)
5.容器基礎知識(Docker, K8S)

## 課程內容 
1.組件規劃網路 : 到一家公司擔當系統架構師須具備的技能/知識
+	VPC : 給公司或客戶建立虛擬網路
+	SubNet : 建立子網路
+	ACL : 如何分配存取權限列表
+	SecurityGroup : 如何分配安全組
+	RouteTable : 路由表 
     * 並藉由Amazon cloud formation 自動話用文本組建網絡
 
2.設計網絡應用 :
+	EC2(Web) : 如何搭建一個虛擬伺服器
+	ELB : 如何做附載均衡(electric loading balance ) (032 033 P.23 AWS 中文入門開發教學)
+	Database : 如何操作一個關係類型數據庫
+	Auto Scaling : 自動化調節user的使用需求(增減服務器的使用)
+	MultiAZ : 多區域(e.g… 台北/ 新北)
+	MultiRegion : 如何部屬多區全球(Region : e.g...東京, 加州...等)

3.AWS服務 : 
+	VPC : 虛擬網路
+	EC2 : 服務器
+	S3 : 文件網路
+	IAM : 如何控制顧客權縣
+	(05 06 AWS 中文入门开发教学)
+	RDS : 如何做關係型數據庫
+	DynamoDB : 如何做Nors(?) 數據庫
+	Lambda(5顆星) : 如何做無服務器應用, 解決很多大型項目解決方案
+	API  Gateway : 與Lambda相聯
+	Route 53 : 
+	CloudTrail : 如何跟蹤用戶行為(0708 AWS 中文入门开发教学)
+	CloudWatch : 如何監控整個用戶系統(04 AWS 中文入门开发教学 )
+	Elastic Beanstalk : 如何自動部屬代碼
+	SQS : 消息的對列, 松耦合的開發(?!)
+	ECR : 如何存儲Docker逕向(?)
+	ECS : Docker的ㄈㄨˊ?
+	 

4.開發流程 :(模擬Github 架構)
+	CodeCommit : 保存代碼, 版本管理
+	CodeBuild : 如何編譯
+	CodeDeploy : 如何自動測試
+	CodePipeline : 如何自動部屬
  
5.進階應用 : 
+	config : 監控每台服務器的設置
+	System Manager : 整台服務器自動化管理
+	CloudFormation : 編寫代碼即能完成整個虛擬網路的構建
+	OpsWorks : 後臺運為操作
+	IOT : 管理平台
+	機器學習 : 人臉識別 美國移民局使用Amazon服務
+	工作流程 : 提供至少三種工作流開發的解決方案
+	移動開發 : Amplify
+	CLI : 命令(行)工具 (AMZ 2種管理資源手法 : A: Browser進行服務管理 or B:  命令(行)工具) → 傳遞參數
+	SDK(Node, js, Python, Go等三種語言) : 透過各種編譯語言去控制AWS資源


## 課程目標 : 
幫助您完成一下系統架構能力

+	實現彈性架構
+	實現高興能架構
+	實現高可用架構
+	實現安全的架構
+	實現成本優化


   
