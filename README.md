# LSA_project
lsa期末報告
# 概念
延勳有強烈的「打鼓上癮症」他只要每隔一段時間不打鼓她就會渾身難受、雙手發抖、講話口吃、暗視、喪失平衡感、情緒失控等戒斷症狀，所以以他請他的組員們開發了這個空氣鼓讓他可以無時無刻都在打鼓，這樣他就可以在上課通勤還有休息時間都一直打鼓，避免發生戒斷症狀時發生憾事。
# 功能
- 一個電子鼓，透過影像識別手揮動的位置來發出聲音
- 有三種樂器可以選擇分別是鼓、鋼琴、吉他
- 使用者可以上傳喜歡的背景樂，來自己根據音樂打節拍
# 使用設備
- raspberry pi 3
- web camera
# 如何快速佈署空氣鼓達人
- 以下皆在樹梅派下
- sudo apt install apache2
- sudo apt install php -y
- sudo apt install git
- cd /etc/www/html 
- sudo git clone https://github.com/SredWh/LSA_project.git
- ifconfig 獲取樹梅派IP
- 電腦要跟樹梅派在同一個內網下
- 電腦根據樹梅派的IP連上apache2就可以開始打鼓
# DEMO影片

# 工作分工
- 陳煒函:程式碼、架伺服器
- 陳延勳:報告、示範、創意
- 李柏緯:寫介紹、攝影剪輯、創意
# 參考資料

# 遇到問題
