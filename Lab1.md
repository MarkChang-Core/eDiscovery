# 使用內容搜尋匯出Exchange Online為PST

### 開啟合規性中心並確認權限

- 內容搜尋這樣功能位於Microsoft 365 合規性中心之中，請前往該位置，或透過連結(https://compliance.microsoft.com/) 登入<br>
  
  > **Tips. 執行內容搜尋請使用Microsoft Edge進行，以確保匯出結果得以正常運作 (eDiscovery Tool)** <br>
  
  ![GITHUB](https://github.com/MarkChang-Core/eDiscovery/blob/main/Image1/image1.jpg)<br>
  
- 在執行內容搜尋功能之前，請先確認操作人員是否已具備正確的權限，請前往「權限」功能中查看<br>

  ![GITHUB](https://github.com/MarkChang-Core/eDiscovery/blob/main/Image1/image2.jpg)<br>

- 進入「權限」後，尋找「eDiscovery Manager」，勾選後即可項下滾動查看到「電子文件探索系統管理員」，若無權限請進行編輯指派<br>

  ![GITHUB](https://github.com/MarkChang-Core/eDiscovery/blob/main/Image1/image3.jpg)<br>  
  
### 執行內容搜尋

- 權限確認完畢後，請前往「內容搜尋」頁面，並點選「新增搜尋」以開始建立搜尋任務 <br>

  ![GITHUB](https://github.com/MarkChang-Core/eDiscovery/blob/main/Image1/image4.jpg)<br>  

- 進入搜尋任務建立頁面後，請輸入一個好記的任務名稱，同時您可以針對任務進行描述以便後續辨別，完成後點選「下一步」 <br>

  ![GITHUB](https://github.com/MarkChang-Core/eDiscovery/blob/main/Image1/image5.jpg)<br>  

- 接著可選擇需要執行的搜尋位置與類別，此處您可依據功能、人員、群組等不同定義建立搜尋任務 <br>

  此處將以 Exchange Online 郵件服務作為範例，請將Exchange 信箱設定為「開啟」，並於後方「選擇使用者、群組或小組」中，
  
  點選並搜尋選中使用者，選擇完成後請點選「完成」，並點選下一步。
  
  > **Tips. 搜尋使用者時，請輸入使用者UPN後，按下鍵盤 Enter 鍵，系統方可開始進行建議的搜尋** <br>

  > **Tips. 當系統搜尋出建議的使用者後，請務必點選該位使用者，否則將不會選中使用者 ** <br>

  ![GITHUB](https://github.com/MarkChang-Core/eDiscovery/blob/main/Image1/image6.jpg)<br>  

- 進入「定義您的搜尋條件」後，請輸入條件篩選運算子，輸入完成後請點選「下一步」 <br>
  
  > **Tips. 此處可進行多條件篩選，搜尋運算子屬於正規表示法，若未輸入代表搜尋全部信箱內容，關於搜尋運算子與陳述式詳細請參考 - 
  > https://docs.microsoft.com/zh-tw/microsoft-365/compliance/keyword-queries-and-search-conditions?view=o365-worldwide#search-conditions**
  
  ![GITHUB](https://github.com/MarkChang-Core/eDiscovery/blob/main/Image1/image7.jpg)<br>  

- 進入最後一個頁面後，將總整您剛剛輸入的搜尋內容任務項目，確認無誤後請點選「提交」，系統便開始執行搜尋任務 <br>

  > ** Tips. 搜尋任務執行的時間會依據搜尋範圍與關聯的資料量大小，可能在數分鐘至數小時內才會完成，而完成時將收到提示郵件。

  ![GITHUB](https://github.com/MarkChang-Core/eDiscovery/blob/main/Image1/image8.jpg)<br>  

- 搜尋任務建立完成後，等待系統搜尋完畢即可開始執行搜尋結果匯出 <br>
  
  ![GITHUB](https://github.com/MarkChang-Core/eDiscovery/blob/main/Image1/image9.jpg)<br>  
  
### 匯出結果


### 下載結果(PST)

