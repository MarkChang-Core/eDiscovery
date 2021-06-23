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

- 在搜尋任務執行完成後，將可於「內容搜尋」的頁面中找到該項任務，點擊後將可查看搜尋任務執行狀況，若執行已完成，則可開始匯出 <br>

  ![GITHUB](https://github.com/MarkChang-Core/eDiscovery/blob/main/Image1/image10.jpg)<br>  
  
- 點選搜尋任務後，於「動作」中展開任務操作內容，並點選「匯出結果」 <br>

  ![GITHUB](https://github.com/MarkChang-Core/eDiscovery/blob/main/Image1/image11.jpg)<br>  

- 在「匯出結果」的彈跳視窗中，可選擇書入選項、匯出選項等，此處可依據需求選定匯出選項，選定完成後點選「匯出」 <br>
  
  > **Tips. 點選匯出後，通常會需要等待數秒鐘的系統響應，此處請勿重新整理頁面以免操作失敗 ** <br>
  
  ![GITHUB](https://github.com/MarkChang-Core/eDiscovery/blob/main/Image1/image12.jpg)<br>  

### 下載結果(PST)

- 在匯出結果完成後，即可到「Export」頁面下載匯出的結果，點擊匯出項目後，選擇「下載結果」 <br>
  
  ![GITHUB](https://github.com/MarkChang-Core/eDiscovery/blob/main/Image1/image13.jpg)<br>  
  
- 當執行「下載結果」後，系統將引導您安裝 eDiscovery Export Tool，請於跳轉頁面中點選「開啟」 <br>

  > **Tips. 由於匯出資料屬於高度機敏性資料，因此eDiscovery Export Tool將透過更安全的連線方式下載

  ![GITHUB](https://github.com/MarkChang-Core/eDiscovery/blob/main/Image1/image14.jpg)<br>
  
- 點選「開啟」後，將提示您執行安裝，請點選「安裝」 <br>

  ![GITHUB](https://github.com/MarkChang-Core/eDiscovery/blob/main/Image1/image15.jpg)<br>

- 當安裝完成後，請於電子文件探索匯出工具中，輸入匯出金鑰與儲存的位置，匯出金鑰可於方才的「下載結果」頁面取得 <br>
  
  > **Tips. 請務必留意，由於下載過程中的網路活動過高，所以建議將搜尋結果下載至本機電腦上的內部磁片磁碟機上的某個位置。
  > 並請留意以下準則已取得最佳體驗 -   
  > - 不要將搜尋結果下載至 UNC 路徑、對應網路磁碟機、外部 USB 磁片磁碟機或同步的商務用 OneDrive 帳戶。
  > - 針對下載搜尋結果的資料夾停用防病毒掃描。
  > - 將搜尋結果下載至不同的資料夾，以進行並行下載工作。** 
  
  ![GITHUB](https://github.com/MarkChang-Core/eDiscovery/blob/main/Image1/image16.jpg)<br>

- 當下載完成後，即可透過如Outlook等工具執行匯入工具進行稽核或查看 <br>

  ![GITHUB](https://github.com/MarkChang-Core/eDiscovery/blob/main/Image1/image17.jpg)<br>
