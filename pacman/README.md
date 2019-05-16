# 課程大綱

本堂課程為人工智慧（Artificial Intelligence）的基礎，內容為透過實作程式來理解如何用電腦科學來產生具有智慧的行為。

應該對 [小精靈 Pac-Man](https://www.google.com/pacman/) 這個遊戲都不陌生吧？遊戲過程玩家會控制裡面的主角小精靈吃掉迷宮裡面的豆子來完成任務。遊戲任務就是小精靈要吃完迷宮裡所有的豆子。

![](https://inst.eecs.berkeley.edu/~cs188/fa18/assets/images/maze.png)

課程將會以 **Pac-Man** 這個遊戲作為練習，從演算法策略：UNINFORMED SEARCH STRATEGIES（無資訊搜尋策略）與 HEURISTIC SEARCH STRATEGIES（啟發式搜尋策略）帶大家實際動手開發來完成一個具有簡易智慧的程式，並使用它來完成小精靈的遊戲任務。

p.s *進階任務是小精靈除了要吃完迷宮裡所有豆子，同時還要避開裡頭的四個鬼魂，如果能順利不被鬼魂的逮住且吃完所有的豆子，那就能過關完成任務。*

Demo 影片:

[![Pac-Man AI Play](http://img.youtube.com/vi/4bjTWd7YVcc/0.jpg)](https://www.youtube.com/watch?v=4bjTWd7YVcc)


課程中將會安排一次演講，邀請樹莓派官方的推廣夥伴來分享麻省理工學院目前正在進行的[小鴨城的專案](https://www.duckietown.org/)，
這個專案是一個視覺化自駕車的學習專案。影像視覺辨識結合人工智慧目前正朝自駕車的應用前進，而 duckie town 正是學術結合產業應用的一個專案，透過影像視覺辨識能夠結合人工智慧演算法或是機器學習方法讓無人車能夠辨識與判斷進而自動選擇正確的路徑行走(內容請[參考](http://raspberrypi-tw.s3.amazonaws.com/slides/20190420_introduction-to-duckietown-project.pdf)）。

Demo 影片:

[![Duckietown](http://img.youtube.com/vi/b0B6S2Ca75Q/0.jpg)](https://www.youtube.com/watch?v=b0B6S2Ca75Q)


# 課程形式

每堂課程會實作為主，透過實際實作結合理論說明。課程使用的程式語言為 **Python**，因此參與此課程需要自行準備筆記型電腦並安裝軟體，課堂中將輔以實作讓同學們可以更快瞭解理論並得到成果。

第一堂課程將會安排快速環境設定與 Python 基礎教學，建議作業系統環境以 Unix 為主（例如: MacOS, Ubuntu 等）
同時會安排一次演講課程，演講者為樹莓派官方推廣夥伴，將會帶來一場麻省理工學院的小鴨城專案演講

預計每課程時間為 3.5 小時。微課程總計花費 5 堂課完成。

每堂課都會有實作，將會請同學將成果上傳到 github（一個原始碼管理平台）作為檢核依據。


# 教材

+ Python 入門: [連結](https://github.com/chairco/CCU_AI)
+ 程式碼: [連結](https://github.com/chairco/CCU_AI)
+ 參考書: [Artificial Intelligence: A Modern Approach 3e](http://aima.cs.berkeley.edu/)


# 授課內容

1. 作業系統環境設定、Unix 基礎指令教學、Python 基礎教學
2. 人工智慧基礎
    + 解決問題的方法-搜尋(search)
    + 搜尋方法的策略(UNINFORMED SEARCH STRATEGIES, HEURISTIC SEARCH STRATEGIES)
3. 實作搜尋方法: Pac-Man
4. 演講-視覺化自駕車專案(小鴨城)


# 課程進度

+ 第一週: 
    + 環境設定
    + Unix 基礎指令教學
    + 基礎 Python 教學
    + 人工智慧 AI 簡介


+ 第二週: 
    1. Uninformed Search
        + Depth First Search (DFS)
        + Breadth First Search (BFS)
        + Uniform Cost Search (UCS)
    2. 實作遊戲

+ 第三週: 
    1. Heuristic Search 
        + Greedy Search
        + A* Search
    2. 實作遊戲

+ 第四週: 
    1. 小鴨城專案演講

+ 第五週: 
    1. CONSTRAINT SATISFACTION PROBLEMS
        + Graph Search
        + CSPs I, II
    2. 實作遊戲
    3. 代理人與強化學習簡介


# 預算編列

+ 餐費
+ 交通
+ 其他
