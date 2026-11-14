先畫了山，上色
再來種樹，一開始樹的顏色不適配現在的unity版本，更改了billbord的大小之後可以順利顯示了
再來放進老虎作為寶可夢
製作精靈球
用 Sphere 加上 Rigidbody,做成 Prefab
製作粒子特效
建立 Particle System,做成 Prefab
寫腳本
PokeballLauncher:在發射點生成球,按空白鍵發射
Pokeball:發射後計時,沒打到目標就重新生成;打到 Tag 為 Target 的物件就通知目標
TargetCatch:被打到時生成粒子特效,並讓目標漸漸變透明後消失
最後測試

Youtube: https://youtu.be/kTXBFP4IbbE?si=-Fg2DM-AqATuVHjl
Github: github.com/Fay756/1151VR-HW5-414261292-TYF/tree/main
