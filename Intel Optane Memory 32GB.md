## [分享\] 第8代 Intel® Core™處理器的使用心得與Intel® Optane™ Memory 32GB桌機改裝實測

Intel在消費市場推出的型號為Optane Memory Series，主要為傳統HDD做加速器的功能，而今天要測試的是桌機板的32GB版本。

Intel® Optane™ Memory 為不同於傳統 NAND 技術之全新記憶元件，亦不受限於目前 NAND 所面臨之困境與瓶頸，而使電子儲存媒體有了質與量之躍進。
[![img](https://cdn1-t17.techbang.com/system/attached_images/2018/07/240939/show/771e448ecba2df1ad7f98d46715fbaed.jpg?1532507645)](https://cdn0-t17.techbang.com/system/attached_images/2018/07/240939/original/771e448ecba2df1ad7f98d46715fbaed.jpg?1532507645)

Intel® 將基於 3D XPoint™ 為基礎而生之Intel® Optane™ Memory，其具備了上述高存取效能、低延遲性以及高耐受度等優勢。為針對消費市場之先驅產品，其憑藉了 3D XPoint™ 之優越特性，而能令使用者原有之機械式硬碟提升至 SSD 層級之體感速度。

廢話不多說，先來看一下Intel® Optane™ Memory的規格內容:
[![img](https://cdn1-t17.techbang.com/system/attached_images/2018/07/240940/show/de0f3830905e08c4b070fda0adc3b03e.jpg?1532507645)](https://cdn2-t17.techbang.com/system/attached_images/2018/07/240940/original/de0f3830905e08c4b070fda0adc3b03e.jpg?1532507645)

此技術是以mSATA規格的小容量SSD來為傳統HDD做加速的功能，在規格上明顯有所提升，搭配上PCIe 3.0x2的最大傳輸頻寬，對於以往在HDD做大容量的存取需求，會大大提升系統開機及資料存取等效率。
[![img](https://cdn1-t17.techbang.com/system/attached_images/2018/07/240941/show/bf3deef409599efaee8fb8741269f588.jpg?1532507895)](https://cdn1-t17.techbang.com/system/attached_images/2018/07/240941/original/bf3deef409599efaee8fb8741269f588.jpg?1532507895)[![img](https://cdn1-t17.techbang.com/system/attached_images/2018/07/240942/show/01464db9a3cb86dd102f9f3adc6e163d.jpg?1532507897)](https://cdn0-t17.techbang.com/system/attached_images/2018/07/240942/original/01464db9a3cb86dd102f9f3adc6e163d.jpg?1532507897)[![img](https://cdn0-t17.techbang.com/system/attached_images/2018/07/240943/show/d6b68c7c9528bd42bb7fbc6225b2fb9d.jpg?1532507899)](https://cdn2-t17.techbang.com/system/attached_images/2018/07/240943/original/d6b68c7c9528bd42bb7fbc6225b2fb9d.jpg?1532507899)

不囉嗦，趕快來進入今天的測試。
此次測試使用 Intel 第八代處理器，應該蠻跟上潮流了!!!
[![img](https://cdn2-t17.techbang.com/system/attached_images/2018/07/240944/show/3925246d9165be8e5863c9dc8eddae82.jpg?1532508523)](https://cdn0-t17.techbang.com/system/attached_images/2018/07/240944/original/3925246d9165be8e5863c9dc8eddae82.jpg?1532508523)

桌機版的Intel® Optane™ Memory 32GB在正面貼紙下方有兩顆3D XPoint IC，型號為MEMPEK1W032GA，3.3V，1.2A
[![img](https://cdn1-t17.techbang.com/system/attached_images/2018/07/240970/show/c9830c698281f611abf1170c343c96f8.jpg?1532511927)](https://cdn1-t17.techbang.com/system/attached_images/2018/07/240970/original/c9830c698281f611abf1170c343c96f8.jpg?1532511927)

也有筆電適用的版本---M10
[![img](https://cdn1-t17.techbang.com/system/attached_images/2018/07/240945/show/b2101cee56093b9ec7f8eac61b0cea7a.jpg?1532508527)](https://cdn0-t17.techbang.com/system/attached_images/2018/07/240945/original/b2101cee56093b9ec7f8eac61b0cea7a.jpg?1532508527)

但是要安裝Intel® Optane™ Memory 需要用到M.2介面，簡單來說就是要新的電腦主機板才有機會使用Intel® Optane™ Memory 這款新產品。
[![img](https://cdn2-t17.techbang.com/system/attached_images/2018/07/240946/show/55395f74dd414de9f8ff813c47793112.jpg?1532508529)](https://cdn2-t17.techbang.com/system/attached_images/2018/07/240946/original/55395f74dd414de9f8ff813c47793112.jpg?1532508529)

改裝前，先來跑一下分才有得比較。
Benchmark測試軟體--- CrystalDiskMark :
https://crystalmark.info/redirect.php?product=CrystalDiskMark
[![img](https://cdn2-t17.techbang.com/system/attached_images/2018/07/240948/show/e7a0be990152ee80abf0f290b765d337.jpg?1532509129)](https://cdn0-t17.techbang.com/system/attached_images/2018/07/240948/original/e7a0be990152ee80abf0f290b765d337.jpg?1532509129)

再來，就是進行Intel® Optane™ Memory 安裝，而直接安裝到M.2介面並不會看到硬體資訊，需要去Intel官網下載快速儲存技術，也就是RST軟體安裝後才會出現32GB裝置。

一鍵安裝 ---Intel® Optane™ Memory 安裝所需軟體連結
https://downloadcenter.intel.com/zh-tw/download/27682/Intel-Optane-?product=99745
[![img](https://cdn0-t17.techbang.com/system/attached_images/2018/07/240953/show/77a97378e00cf342ac389f50f377c425.jpg?1532509501)](https://cdn2-t17.techbang.com/system/attached_images/2018/07/240953/original/77a97378e00cf342ac389f50f377c425.jpg?1532509501)[![img](https://cdn0-t17.techbang.com/system/attached_images/2018/07/240954/show/3b6784ea2ac03638ed43d6efdd5a6d60.jpg?1532509501)](https://cdn1-t17.techbang.com/system/attached_images/2018/07/240954/original/3b6784ea2ac03638ed43d6efdd5a6d60.jpg?1532509501)

再來就是啟用Intel® Optane™ Memory 的功能，取名Memory並非指常見的系統記憶體，而是做為傳統HDD所用的加速器。
[![img](https://cdn2-t17.techbang.com/system/attached_images/2018/07/240956/show/4b2c077034c7d1480f15fbf1f6a17e1c.jpg?1532509772)](https://cdn1-t17.techbang.com/system/attached_images/2018/07/240956/original/4b2c077034c7d1480f15fbf1f6a17e1c.jpg?1532509772)
[![img](https://cdn0-t17.techbang.com/system/attached_images/2018/07/240955/show/64a367dc88a41e327e97d76d9aaffc95.jpg?1532509643)](https://cdn2-t17.techbang.com/system/attached_images/2018/07/240955/original/64a367dc88a41e327e97d76d9aaffc95.jpg?1532509643)

安裝Intel® Optane™ Memory 軟體後，需要重新開機。
[![img](https://cdn0-t17.techbang.com/system/attached_images/2018/07/240958/show/4eb02bef4d8248d24e98d1ea00873e1b.jpg?1532510192)](https://cdn2-t17.techbang.com/system/attached_images/2018/07/240958/original/4eb02bef4d8248d24e98d1ea00873e1b.jpg?1532510192)

系統會切換SATA至支援模式。
[![img](https://cdn1-t17.techbang.com/system/attached_images/2018/07/240957/show/a77aeaaa0b98707a82ec906e7ceaca8a.jpg?1532509959)](https://cdn0-t17.techbang.com/system/attached_images/2018/07/240957/original/a77aeaaa0b98707a82ec906e7ceaca8a.jpg?1532509959)

開機僅入系統畫面後，就可以看到多一個 Intel® Optane™ Memory 磁碟機。
[![img](https://cdn0-t17.techbang.com/system/attached_images/2018/07/240959/show/2c095dde7f43b778a85eae79e0230b32.jpg?1532510193)](https://cdn0-t17.techbang.com/system/attached_images/2018/07/240959/original/2c095dde7f43b778a85eae79e0230b32.jpg?1532510193)

按下啟用後，會出現清除Intel® Optane™ Memory資料的警告，勾選後按下繼續，便會清除Memory資料，以及對Memory做最佳化，這段需要花費一段時間，將系統或是一些常用的軟體轉移至Intel® Optane™ Memory 中，但是完成後也要重新開機才可以正常使用，開機過程中就可以感受到加速所得到的效果。
[![img](https://cdn0-t17.techbang.com/system/attached_images/2018/07/240961/show/5c90b18061c266e7afd66720c9e914dc.jpg?1532510710)](https://cdn2-t17.techbang.com/system/attached_images/2018/07/240961/original/5c90b18061c266e7afd66720c9e914dc.jpg?1532510710)[![img](https://cdn0-t17.techbang.com/system/attached_images/2018/07/240962/show/728d6041f7fda5b3cdbfd1cfc12d00ac.jpg?1532510711)](https://cdn2-t17.techbang.com/system/attached_images/2018/07/240962/original/728d6041f7fda5b3cdbfd1cfc12d00ac.jpg?1532510711)
[![img](https://cdn0-t17.techbang.com/system/attached_images/2018/07/240960/show/dd2002552208b5dbc446fcb98a75b696.jpg?1532510464)](https://cdn0-t17.techbang.com/system/attached_images/2018/07/240960/original/dd2002552208b5dbc446fcb98a75b696.jpg?1532510464)

好不容易安裝成功啟用了，真是感動~~~~!!!!
[![img](https://cdn0-t17.techbang.com/system/attached_images/2018/07/240968/show/50115c0f164e8d50f423da95a9f557fb.jpg?1532511813)](https://cdn1-t17.techbang.com/system/attached_images/2018/07/240968/original/50115c0f164e8d50f423da95a9f557fb.jpg?1532511813)

這時，會看到磁碟管理員中顯示既有硬碟之磁區資訊:
[![img](https://cdn1-t17.techbang.com/system/attached_images/2018/07/240964/show/1b35119a7e2d279e87883fd4bc40f1bd.jpg?1532510847)](https://cdn0-t17.techbang.com/system/attached_images/2018/07/240964/original/1b35119a7e2d279e87883fd4bc40f1bd.jpg?1532510847)

開啟Intel固態硬碟工具箱也可以看到左邊有Intel® Optane™ Memory 的資訊右方是本次加速的HDD，規格為2.5吋與容量為2TB，也可以再加上第二顆HDD，但是並不能為第二顆HDD做加速。
Intel® Optane™ Memory 所採用之控制器並不會針對資料進行壓縮加速，一開始先看到此顆2.5吋2TB的原始效能CrystalDiskMark測試，已經很久沒用HDD當系統碟，使用起來的遲緩感讓人很懷念過去的電腦時代…HDD速度太慢是因為架構的因素讓搜尋時間過長，加上內外圈傳輸速度落差過大。

緊接著，就要看看改裝後，會有什麼驚人效果。
改裝後CrystalDiskMark Benchmark測試結果。
[![img](https://cdn0-t17.techbang.com/system/attached_images/2018/07/240965/show/af5fa683a715a8487f2ef59ffde0412f.jpg?1532511057)](https://cdn2-t17.techbang.com/system/attached_images/2018/07/240965/original/af5fa683a715a8487f2ef59ffde0412f.jpg?1532511057)

上面兩個改裝前後跑分比較結果，發現安裝Intel® Optane™ Memory 之後，成績真的嚇嚇叫，果然有明顯的差異，真是給他大聲地拍拍手!!!

而Intel® Optane™ Memory 可加速一顆不限容量與不限分割成幾個磁區的HDD，並且可加速C與D磁區是較有優勢的地方。

值得一提的是溫度表現，現今多數高階M.2 SSD在高負載下溫度約為72~80度，而入門M.2 PCIe的Intel 600P最高溫度也會達到70度，Optane Memory雖無法用軟體測溫，但在高負載寫入測試時，個人用手指觸碰得溫度感約落在40~50度左右。

開機看從看畫面到進入Windows 10桌面僅需4秒算是相當地快速，進去Windows桌面後至讀取完要看每台電腦所安裝的常駐軟體多寡而定，面對Windows 10大容量的檔案傳輸，Optane Memory在第二次使用時就可達到最佳的效能。

個人覺得Intel® Optane™ Memory 技術最實用的莫過於對於影像處理或是遊戲軟體的應用，普遍覺得256~512GB SSD當作系統碟再安裝多款遊戲其實容量是不太足夠，現在許多遊戲檔案都相當地肥大，一個遊戲時常需要用到幾十GB，甚至接近上百GB的也有。

測試遊戲軟體時，連點遊戲兩下的同時，左手開始按計時，誤差時間約在1秒內。

Assassin's Creed Syndicate，資料夾容量為41.2GB
HDD=>出現畫面28秒 / 進到開始畫面66秒
Intel® Optane™ Memory 加速=>出現畫面12秒 / 進到開始畫面52秒
[![img](https://cdn1-t17.techbang.com/system/attached_images/2018/07/240966/show/8d527d43b58584f298115aedcdbf67fc.jpg?1532511058)](https://cdn2-t17.techbang.com/system/attached_images/2018/07/240966/original/8d527d43b58584f298115aedcdbf67fc.jpg?1532511058)

Tom Clancy's Rainbow Six Siege，資料夾容量為77.6GB
HDD=>出現畫面55秒 / 進到開始畫面100秒
Intel® Optane™ Memory 加速=>出現畫面20秒 / 進到開始畫面60秒
[![img](https://cdn1-t17.techbang.com/system/attached_images/2018/07/240971/show/0cfc6fbe29fc968d5f9591545fddafa6.jpg?1532512713)](https://cdn1-t17.techbang.com/system/attached_images/2018/07/240971/original/0cfc6fbe29fc968d5f9591545fddafa6.jpg?1532512713)

從網路上得知Intel® Optane™ Memory 的價位，會跟很多網友反應差不多，覺得每GB單價拿來與SSD比較會覺得高上許多，不過產品定位在對HDD加速器的功用，加上實際使用比較過後，Intel® Optane™ Memory 確實有它的優勢存在，對於有傳統HDD的族群也會有其需求，售價約比TLC SATA3 SSD要低一些，如果有HDD並放入大容量的遊戲軟體，或經常會使用到HDD內的軟體或檔案，加上SSD當系統碟又不太夠用,那Intel® Optane™ Memory 配置不失為一個好選擇，這項新技術支援( Kaby Lake-S/Coffee Lake-S/Skylake-S ) 平台，換新電腦的使用者才有機會能使用，希望未來Intel能推出更多3D XPoint技術的產品，像是更高容量的Intel® Optane™ Memory 或導入消費級M.2 SSD

測試總結
實際測試比較後，Intel® Optane™ Memory 搭配一般的HDD或是SSD固態硬碟時，在讀取效能方面都有相當不錯的加速表現，而對於一般HDD硬碟的加速效果更是明顯。不過，因為本身寫入規格沒有太高，所以搭配固態硬碟使用時，在寫入方面沒有太明顯的加速效能。
由於Intel® Optane™ Memory 有著Intel處理器、Intel系列主機板以及Windows 10作業系統等軟硬體規格限制，所以對於舊平台的使用者而言，最好搭配方法是重新組裝。
再來，就整體而言，雖然Intel® Optane™ Memory 確實能夠達到明顯的加速效果，但由於諸多軟硬體限制，加上與SSD固態硬碟的CP值價格差異不大，是否只是個過渡型的產品，還是等看日後大容量Intel Optane SSD出現或許會有比較高實用性吧！

詳細資訊，請參考下列網站連結:
https://www.autobuy.tw/3c/prod_218815_13781

