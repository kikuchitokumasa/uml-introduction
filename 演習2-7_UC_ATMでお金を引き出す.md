**ユースケース図** 
ATMで「お金を引き出す」
**概要**
銀行のATMを利用して、自分の口座からキャッシュカードで必要なお金を引き出します。
**アクター**
利用者
**事前条件**
アクターが口座とキャッシュカードを持っていること。
**事後条件**
アクターの口座から指定された金額が引き出されること。
**基本フロー**
+ ATMにキャッシュカードを入れるとユースケースは開始する
+ 引き出すを選択する
+ 暗証番号を入力する
+ 引き出す金額を入力する
* ATMから表示された金額を確認する  
+ お金を引き出す
+ キャッシュカードを取り出してこのユースケースは終了する

**【代替フロー】**  
    A-1:暗証番号を間違えたらお金を引き出せない  
1. システムはお金の引き出しの中止を確認する  
2. お金の引き出しは中止  


E-1:引き出すお金がない  
1. お金を引き出すことを中止する  
**【例外フロー】**  


**ユースーケース名**  
    ATMで「お金を引き出す」  
**【基本シナリオ】**  
1. キャッシュカードを入れる  
2. お金を引き出すを選択する  
3. 暗証番号「＊＊＊＊」を入力する  
4. 引き出す金額「XXXX」を入力する  
5. ATMから表示された金額「XXXX」を確認する  
6. お金を引き出す  
7. キャッシュカードを取り出す  
**【例外シナリオ】**  