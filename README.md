# C-BlackJack
21點撲克牌遊戲

## 遊戲規則
1.遊戲的目標是接近或達到21點，但不能超過21點。<br>
2.牌面點數：2-10的牌按照其點數計算；J、Q、K按照10點計算；A 牌當作 11 點(本程式中以‘1’當作‘A’)，但是第二個 A 牌以後皆為 1 點<br>
3.遊戲開始時，玩家和莊家會分別發兩張牌。<br>
4.玩家可以看到自己的兩張牌，但只能看到莊家的一張牌。<br>
5.玩家可以選擇繼續抽牌（Hit）或停止抽牌（Stand）。<br>
6.如果玩家的牌面點數超過21點，玩家爆牌，遊戲結束，莊家獲勝。<br>
7.如果玩家選擇停止抽牌，輪到莊家進行操作。<br>
8.莊家會根據固定的規則來決定是否抽牌。莊家在取得17點之前必須要牌，莊家如果拿牌五張而沒有爆牌則視為莊家勝利。<br>
9.如果莊家的牌面點數超過21點，莊家爆牌，玩家獲勝。<br>
10.如果莊家選擇停止抽牌，比較玩家和莊家的牌面點數。點數更接近21點的一方獲勝。<br>
11.如果玩家和莊家的點數相同，則平局。<br>

## 遊玩方法
依照畫面指示遊玩

## 遊戲畫面
![image](https://github.com/tohousanae/C-BlackJack/assets/122202405/cc8d743f-67d1-4fec-838d-54eebe615dfa)![image](https://github.com/tohousanae/C-BlackJack/assets/122202405/2cf273d3-eac5-4dd3-a760-41a76d95879f)
![image](https://github.com/tohousanae/C-BlackJack/assets/122202405/356207eb-24ce-45c6-a816-12d663845dc9)

## 注意事項
請確保系統文字格式為utf-8，可在windows當中的"控制台->變更日期、時間或數字格式->系統管理->變更系統地區設定->打勾"Beta: Unicode UTF-8 提供全球語言支援(U)"，並重新啟動。如下圖:
<br>
![image](https://github.com/tohousanae/C-BlackJack/assets/122202405/b1bd3bb4-8aa0-4dc1-8475-82591e325a4d)

## 已知bug
1.要牌階段輸入h或f以外的指令會出現再來一局對話框

## 參考文獻
１.https://aries.dyu.edu.tw/~thhu/C1/hw05_4.pdf
