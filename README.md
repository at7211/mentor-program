# 程式導師實驗計畫

## 這是什麼

[程式導師實驗計畫](https://medium.com/@hulitw/mentor-program-b5f96ae1eed1)是一個為期四個月的計畫，要求學生全程參與（每週至少付出四十小時），希望能在結業時培養出合格的（意思就是找得到工作）的工程師。

## 課程目標

### 綜合能力
1. 具有找資料的能力，能夠知道如何找到相關資訊
2. 具有分析問題的能力，能夠快速定位問題
3. 知道如何解決問題，包括但不限於拆解問題、簡化問題、轉化問題
4. 解決問題後能夠重新歸納並整理

### 工具能力

1. 後端：知道後端原理，知道什麼是資料庫、server，可以寫出簡單的網站並且自己部署
2. 前端：知道前端原理，HTML、CSS、JavaScript，知道 Ajax 以及如何與後端串接
3. 資安：基本資安概念，SQL Injection、XSS、CSRF

## 課程規則

1.每天請把自己昨天做的事情以及今天預計要做的事情貼在 slack channel，可直接複製以下範例並且更改：

```
*昨天*
- 完成 git 安裝
- 解 codewar 題目：Opposite number

*今天*
- 解 codewar 題目：Opposite number
- 寫作業：好多星星

```

2.有任何意見回饋或是課程相關問題，都可以直接私訊導師（@huli）討論，如果想要匿名反應的話，也可以填寫[匿名表單](https://goo.gl/forms/Sge0EPSBO0cS3LGC3)

3.請在 Github 開一個 repo，把 issue 頁面當作 blog 紀錄心得，順便練習 Markdown 語法。[範例](https://github.com/Lidemy/blog-example)


## 課程進行方式

每週一、四晚上九點以及週日晚上八點進行直播教學，其餘時間可利用 slack 群組隨時發問。每次教學時間約為一小時至兩小時。

週一會把這期的課程內容大概講過一遍，而學生利用週二以及週三自學並且嘗試練習題目。

週四會總結大家這兩天以來的問題一併回答，並且重新把課程內容再講過一遍（或是補完週一上不完的）。

週日幫這週課程做總結，講解作業題目以及批改作業。

## 課程大綱

從 2018/01/29 至 2018/05/29	，為期四個月的課程，一共約十七週。每週的開始為禮拜一，結束為禮拜日。

### 第一週（01/29 ~ 02/04）：程式基礎

大致介紹整個計畫以及帶學生看過一次課程大綱，接著說明整體架構，介紹各種不同工程師職位所負責的工作內容並著重在網頁工程師的介紹。

Mindset 建立：

1. 不要害怕問問題，每個問題都值得被提出來，你的問題可能也是其他人的問題
2. 問問題前應該要自己查詢資料（有些很難查的直接問也可以）
3. 你有老師讓你盡量問，反正問就對了，有錯的話我會提醒你
4. 重點是「目的」，而不是「手段」，持續問為什麼為什麼為什麼為什麼

建置基礎環境，例如說 command line tool、git 以及 node.js。

複習程式基礎，像是變數、陣列、迴圈、判斷式以及函式（以 ES5 為例）並介紹常用內建函式如 replace, indexOf, split, map, filter, join, parseInt 以及 Math 等等。

知道如何寫簡單的 unit test，並且自己寫 test case 檢驗自己的函式。

[作業連結](/homeworks/week1)

#### 目標：

- [ ] 知道程式如何執行
- [ ] 了解寫程式的本質只是一行行的指令
- [ ] 了解前端與後端的區別
- [ ] 能說出從發出一個 request 到接收 response 中間發生的事
- [ ] 了解不同載具的差異（Desktop、Mobile、Web）
- [ ] 了解基本的 command line 指令
- [ ] 知道 Git 在做什麼
- [ ] 知道 add, commit, push, pull 等基本 Git 指令
- [ ] 了解常用內建函式
- [ ] 熟悉程式語法並解決基礎問題


### 第二週（02/05 ~ 02/11）：前端基礎（上）

本週將會正式進入到前端課程的領域，開始用 HTML 與 CSS 打造出基本的網頁，並且利用 media query 實現 RWD（Responsive Web Design）。

HTML 的部分就簡單帶過幾個常見的 Tag，帶到 head 的一些屬性跟設定。

主要會著重在 CSS 的部分，並且讓大家多多練習。

#### 目標：

- [ ] 知道 HTML 是什麼
- [ ] 知道 CSS 是什麼
- [ ] 知道 inline、block 跟 inline-block 的區別
- [ ] 知道什麼是 box model
- [ ] 知道 position 的所有屬性及其差別
- [ ] 知道 :hover, :before, :after
- [ ] 知道 :nth-child
- [ ] 熟悉 CSS selector


### 第三週（02/12 ~ 02/18）：停課一週
本週由於老師放假加上農曆新年，停課一週，但還是隨時開放問問題。

### 第四週（02/19 ~ 02/25）：前端基礎（中）

這一週將會進入到 JavaScript，讓網頁變得有互動性，並結合 `<form>` 做表單驗證，或是讓大家寫出簡單的網頁應用程式。

除此之外，也會在這週講 API 串接，讓大家對什麼是 API 有基本的概念，並且實作 Ajax。

#### 目標：

- [ ] 知道 JavaScript 是什麼
- [ ] 知道 JavaScript 跟 Java 的關係
- [ ] 知道 DOM 是什麼
- [ ] 知道如何用 JavaScript 操控 DOM 物件
- [ ] 知道什麼是 API
- [ ] 知道什麼是 Ajax
- [ ] 知道如何存取跨網域的資源（CORS）
- [ ] 知道什麼是 JSON
- [ ] 知道什麼是 JSONP 及其原理

### 第五週（02/26 ~ 03/04）：後端基礎（上）

前端基礎打得差不多以後，就要進入後端的課程，這次課程會以 PHP 為主要的語言，Node.js 為輔助。

這週的課程會講解 PHP 基本觀念、語法，並且教大家安裝設定 MySQL，寫出簡單的 CRUD 應用。

#### 目標：

- [ ] 知道 PHP 是什麼
- [ ] 知道前端與後端的差別
- [ ] 知道什麼是資料庫
- [ ] 了解基本 SQL 語法
- [ ] 寫出基本 CRUD 應用

### 第六週（03/05 ~ 03/11）：後端基礎（中）

這週會延續之前的章節，打造出一個比較完整的產品，一步步把後端變得更複雜一點，並且加強會員系統、權限管理等等。

#### 目標：

- [ ] 知道什麼是 Session
- [ ] 知道什麼是 Cookie
- [ ] 知道 Session 與 Cookie 的差別
- [ ] 知道雜湊演算法原理以及應用
- [ ] 知道什麼是 SQL Injection 以及如何防範
- [ ] 知道什麼是 XSS 以及如何防範
- [ ] 知道什麼是 CSRF 以及如何防範


### 第七週（03/12 ~ 03/18）：前端基礎（下）

首先帶大家串接之前自己寫出來的 API，把前端介面用 Ajax 改寫，使網頁互動性變得更高。讓大家熟悉 jQuery，把現有應用用 jQuery 改寫一次。

版面的部分則利用 Bootstrap 搭配 Bootswatch 讓介面變得美觀。利用網格系統實作 RWD。

#### 目標：

- [ ] 知道 jQuery 是做什麼的
- [ ] 知道 jQuery 與 vanilla js 的差別
- [ ] 知道如何與自己寫的 API 串接
- [ ] 知道什麼是 Bootstap
- [ ] 知道 Bootstap 原理及如何應用
- [ ] 知道什麼是網格系統以及如何應用在 RWD

### 第八週（03/19 ~ 03/25）：後端基礎（下）

有了自己的前後端程式之後，就可以開始來部署了。這週的重點會放在帶大家直接去買主機（AWS、Digital Ocean、Linode），並且了解如何連上主機。

也會讓大家購買自己的網域，理解如何將網域以及主機串連起來，讓大家可以連線到你的網站。

在這個章節也會讓大家理解後端基本架構（NAT、Load balancer、DB replication 等等）

#### 目標：

- [ ] 了解後端架構
- [ ] 知道虛擬空間、虛擬主機以及實體主機的差別
- [ ] 知道什麼是網域
- [ ] 知道如何設定網域以及原理
- [ ] 知道如何用 SSH 遠端連線到自己的主機
- [ ] 知道如何部署應用程式

### 第九週（03/26 ~ 04/01）：前端中階（上）

在被 CSS 折磨這麼久之後，終於有機會用程式化的方法來撰寫 CSS，這週將介紹幾個不同的 CSS preprocessor（LESS, SASS, Stylus），讓學生自行選擇看順眼的並且練習，把之前的 CSS 都改寫。

也會介紹到 postcss，讓 CSS 變得更簡單。

 #### 目標：

- [ ] 了解 CSS 預處理器的目的以及原理
- [ ] 知道 postcss 是什麼

### 第十週（04/02 ~ 04/08）：前端中階（下）

這週將學習把工作自動化，利用 gulp 管理工作流程，避免繁瑣的手動操作。

也會講到 Webpack 誕生的理由以及模組化的 JavaScript 開發，讓學生理解為何需要使用 Webpack。

會需要學生做出一個簡單的 todo list。

 #### 目標：

- [ ] 了解 gulp 的目的以及原理
- [ ] 了解 webpack 的目的以及原理
- [ ] 熟悉如何使用 webpack 進行模組化開發
- [ ] 熟悉如何使用 gulp 建構自動化工作流程
- [ ] 能夠快速打造出基礎環境

### 第十一週（04/09 ~ 04/15）：後端框架（上）

基礎 Laravel 課程。

### 第十二週（04/16 ~ 04/22）：前端框架（上）

終於要進入到前端框架 React 了（雖然嚴格來說 React 並不是一個框架，但搭配其他各種 React 生態系成員，其實就算是一個框架了）。

這週會學習到 React 的基本應用以及原理，了解為什麼我們需要使用 React。

 #### 目標：

- [ ] 了解 React 的目的以及原理
- [ ] 了解我們為什麼需要 React
- [ ] 了解 React 跟之前使用 jQuery 的區別
- [ ] 了解 state 跟 props 的不同
- [ ] 學習以元件的角度去看整個 App

### 第十三週（04/23 ~ 04/29）：前端框架（下）

接續之前的 React，這一週會讓你的 Web App 變得更加完整，導入 React Router、Redux 以及 Redux Observable。

 #### 目標：

- [ ] 了解 Redux 的目的以及原理
- [ ] 了解我們為什麼需要 Redux
- [ ] 了解 React Router 的目的
- [ ] 知道什麼是 Single Page Application
- [ ] 了解現在的前端與以往的差別

### 第十四週（04/30 ~ 05/06）：後端框架（下）

延續之前的課程，繼續講解 Laravel，如果不想走後端的，這邊可以跳過。

### 第十五週（05/07 ~ 05/13）：Final Project

接下來幾週都會讓同學自己做出屬於自己的 Final Project，可以與其他人合作，也可以選擇一個人單打獨鬥。


### 第十六週（05/14 ~ 05/20）：Final Project

### 第十七週（05/21 ~ 05/27）：Final Project Demo

作品展示。

## 自我練習

Codewar 是一個程式解題平台，靠這些題目，可以訓練自己對語法的熟悉度以及維持手感，更進階的題目則是能夠訓練思考邏輯以及解題方法。

我依照難度整理出了一些題目，平常做作業卡關或是沒事做的時候，都可以解一下這些題目。

[Codewar 題目列表](/codewar.md)

## Tech Stack

這邊列舉這堂課程所有用到的工具。

1. 課程直播：Youtube
2. 群組聊天：Slack
3. 交作業：Github + Github Classroom + Travis CI 自動批改
4. 練習題目：Codewar

