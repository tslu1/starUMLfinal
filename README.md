# 南華大學軟體工程-期末報告
# 利用“4+1”視圖建模方法進行“精準扶貧管理系統”的軟件架構設計
## 組員:11024254蔡尚原 11024255蔡尚倫
### 1 “4+1”視圖建模方法
##### 软件架构常用模型就是视图模型，类似于RM-ODP的视点模型，可以从多个角度描述一个复杂的软件系统。最流行的视图模型就是“4+1”视图模型，它由五个视图组成，包括场景视图、逻辑视图、进程视图、物理视图和开发视图，如图1-1所示。我们可以粗略地把“4+1”视图模型看作是参照软件生命周期五个阶段建立的视图模型，虽然实际上每个视图描述的内容并不是局限于生命周期的一个阶段，但显而易见的是，除了结构要素之外，这种视图模型也包含了流程要素。
![1](1.png)
##### “4+1”視圖模型實際上使得有不同需求的人員能夠得到他們對於軟件體系結構想要了解的東西。系統工程師先從物理視圖，然後從過程視圖靠近體系結構。最終使用者、客戶、數據專家從邏輯視圖看體系結構；項目經理、軟件配置人員從開發視圖看體系結構。
### 2 利用“4+1”視圖建模方法進行“精準扶貧管理系統”的軟件架構設計過程
#### 2.1 精準扶貧管理系統內容描述
##### 精準扶貧信息化平台可實現全省貧困戶信息的全面、準確統計；對扶貧項目、扶貧資金的全面公開、監督管理；對扶貧過程進行有效跟蹤、管理；對扶貧結果進行實時查詢；為扶貧工作的更進一步開展積累有效的基礎數據，為全省扶貧的大數據趨勢分析奠定良好的基礎。精準扶貧信息化平台由精準扶貧管理系統支持，該系統適用於省級、市級扶貧主管部門對扶貧信息數據的及時準確統計，扶貧信息的精準推送，為扶貧工作提供互動溝通的平台，實現對扶貧工作的信息化管理。	
#####	精準扶貧管理系統主要分為四個部分，精準識別、精準幫扶／管理、幫扶成效評價意見反饋和大數據分析。整個精準扶貧信息化平台的應用貫穿貧困戶精確識別、精確幫扶、精確管理、幫扶成效評價、意見反饋、大數據分析等整個扶貧全過程；在貧困戶精確識別階段可實現扶貧信息公示、評選結果反饋、建立貧困戶檔案和數據庫等功能；在幫扶階段，可為精確幫扶、精確管理提供信息化手段支撐，包括貧困戶信息管理、陽光操作管理、扶貧事權管理；在幫扶成效評估和意見反饋階段，可提供基於互聯網+的在線評價和網站在線反饋功能；通過對系統運行積累的大數據進行系統分析，可提供對貧困原因、幫扶措施、幫扶效果、貧困戶分布等的關聯性分析，趨勢分析、預測，綜合數據分析，數據挖掘，領導輔助決策，統計報表等功能。具體內容描述如圖2-1-1所示。	
#####	具體來講，基於“精準扶貧信息化平台”主要包括全省四級一體的數據平台、基於互聯網的外網網站、各級人員使用的手機APP客戶端、扶貧事權管理系統和扶貧大數據分析系統等主要內容，並建立相應的信息化支撐體系。
