## **CAMPro 軟體安裝手冊**



 **1. 安裝 CAMPro**

* [**1-1 安裝 Windows 版本**](#1-1)
* [**1-2 單機配置**](#1-2)
* [**1-3 多機配置**](#1-3) 


-------

**2. 啟動 CAMPro**


* [**2-1 執行 CAMPro**](#2-1)
* [**2-2 設定使用者帳號**](#2-2)
* [**2-3 設定 DataBase**](#2-3)
* [**2-4 License 機制說明**](#2-4)

----

**3. 如何更新 CAMPro**

* [**3-1 更新版本**](#3-1)
* [**3-2 更新 License**](#3-2)


----

<h2 id="1-1"> 1-1 安裝 Windows 版本 </h2>




- 點選 "**install.exe**" 應用程式。
 
![](./icon-install-package/1.png)

- 選擇安裝語言(說明以繁體中文為例)。



![](./icon-install-package/2.png)

- 目的資料夾：可以選擇要安裝之路徑，範例以 "**C:\CAMPro**" 為例。

- 安裝類型：點選 "**初次安裝**"。

- 點選 "**下一步**"。

![](./icon-install-package/3.png)



###Set Environment
- 選擇 DataBase 路徑(這會是未來料號儲存的路徑)，範例以 C:/CAMPro/fw 為例。
- 設定您的登入帳號，預設值：g。
- 設定您的登入密碼，預設值：g。
- 設定 CAMPro Server IP，依據您的模式請參閱 [**1-2 單機配置**](#1-2) 或 [**1-3 多機配置**](#1-3) 。
- 設定 Server Port，欄位請輸入 8090、8898、8080、或 8888，範例以 8888 為例。

- 以上設定完成後點選 "**下一步**"。




![](./icon-install-package/5.png)





- 確認以上資料後，請點選 "**Install**"。


![](./icon-install-package/6.png)


- 安裝成功通知。

![](./icon-install-package/7.png)





<h2 id="1-2"> 1-2 單機配置 </h2>


- 選擇 DataBase 路徑(這會是未來料號儲存的路徑)，範例以 C:/campro/fw 為例。
- 設定您的登入帳號，說明以 g 為例。
- 設定您的登入密碼，說明以 g 為例。
- 設定 CAMPro Server IP，欄位請輸入目前已插入 License Key 的主機 Server IP 或 "**localhost**" 或 "**127.0.0.1**”，範例以 "127.0.0.1" 為例。
- 設定 Server Port，欄位可以輸入 8090、8898、8080、或 8888，範例以 8888 為例。(備註：**Port 必須與要連入的 Server 設定的 Port 一致!**)



![](./icon-install-package/5.png)






<h2 id="1-3"> 1-3 多機配置 </h2>

- 選擇 DataBase 路徑(此路徑為未來料號儲存的路徑)，範例以 C:/CAMPro/fw 為例。
- 設定您的登入帳號，說明以 g 為例。
- 設定您的登入密碼，說明以 g 為例。
- 設定 CAMPro Server IP，欄位請**輸入您要連入的 Server IP**。
- 設定 Server Port，欄位請輸入 8090、8898、8080、或 8888，範例以 8888 為例。(備註：**Port 必須與要連入的 Server 設定的 Port 一致!**)


![](./icon-install-package/5-1.png)




<h2 id="2-1"> 2-1 啟動CAMPro </h2>

- 將 USB Key 插入電腦。

- 進入路徑 C:\campro\1.1。 

- 先開啟 "**ezServer**" 並確認要連入的主機 ezServer 是否也已經啟動，然後再點選 "**camPro.exe**" 即可。



![](./icon-install-package/8.png)



![](./icon-install-package/9.png)


<h2 id="2-2"> 2-2 設定使用者帳號 </h2>

- 輸入 Login Name: g。

- 輸入 Password: g。

- 說明皆以預設值設定 g 為例。

![](./icon-install-package/12.png)

- 您仍然可以開啟 CAMPro 軟體後點開 "**Options**" 選 "**Users**" 重新設定使用者帳號與密碼。

![](./icon-install-package/17-1.png)

![](./icon-install-package/17.png)


<h2 id="2-3"> 2-3 設定 DataBase </h2>

- DataBase 已於初次安裝時建立路徑。

![](./icon-install-package/5-2.png)

- 您仍然可以開啟 CAMPro 軟體後點開 "**Options**" 選 "**Databases**"，再點選 "**Change**" 重新設定路徑。


![](./icon-install-package/10.png)

![](./icon-install-package/18.png)


<h2 id="2-4"> 2-4 License 機制說明 </h2>

- 您可以開啟 CAMPro 軟體後點開 "**Options**" 選 "**Licenses**" 來查閱您的 Licenses 到期日。

![](./icon-install-package/16-1.png)

![](./icon-install-package/16.png)


<h2 id="3-1"> 3-1 更新版本 </h2>

### 安裝包更新方式：

- 點選 "**install.exe**" 應用程式。


![](./icon-install-package/1.png)

- 目的資料夾：要安裝之路徑，範例以 "**C:\CAMPro**" 為例。

- 安裝類型：點選 "**版本更新**"。

- 點選 "**更新**"。

![](./icon-install-package/6-1.png)







### 手動更新方式：將新的 1.1 資料夾複製貼上到 CAMPro 資料夾內以取代舊的 1.1 資料夾。
 
![](./icon-install-package/13.png)


----------


<h2 id="3-2"> 3-2 更新 License </h2>


### 安裝包更新方式：

- 點選 "**install.exe**" 應用程式。

![](./icon-install-package/1.png)

- 目的資料夾：要安裝之路徑，範例以 "**C:\campro**" 為例。

- 安裝類型：點選 "**License 更新**"。

- 點選 "**更新**"。


![](./icon-install-package/7-1.png)





### 手動更新方式：
- 進入路徑 C:\campro\share\license。
- 手動更新方式：將新的 license 檔案複製貼上到 license 資料夾內以取代舊的 license。

![](./icon-install-package/14.png)





