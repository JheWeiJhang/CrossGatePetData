# CrossGatePetData
針對火箭牌算檔器，提供魔力寶貝永恆初心版本的寵物資訊

檔案下載可以從這裡：
http://cgsword.com/download.htm 的 http://cgsword.com/download/CGCalculator.msi
主要使用方式可以參考下面這個網站
https://www.bluecg.net/forum.php?mod=viewthread&tid=147093

如果你想自己新增檔案內容，可以參考上方連結，下面內容解取自上方連結
寵物資訊就是在config.ini裡面，檔案內容格式如下
XXXX=AAAA;B;CC;DD;EE;FF;GG
  AAAA
    寵物名稱
  B為種族
    0為野獸
    1為不死
    2為飛行
    3為昆蟲
    4為植物
    5為特殊
    6為金屬
    7為龍型
    8為人型
    9為邪魔
  CC;DD;EE;FF;GG為檔次分佈，
    分別為體力;力量;強度;速度;魔法。

該Git的Repo使用方式如下
1.把這邊的的config.ini的檔案內容全部複製到C:\Program Files (x86)\CGCalculator\config.ini檔案內，存檔離開。
2.重新啟動CGCalculator.exe就可以使用新的檔案內容。

為什麼選用火箭牌算檔器?
1. 鼠王算檔器被windows內建的掃毒認為是有問題的，當然你可以選擇加入安全區域，無視這個警告直接使用
2. 魔物觀測者新增的寵物超過150個之後的都無法顯示出來，使用上比較麻煩
