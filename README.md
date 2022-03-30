# 計算google mobility和每日新增案例數的相關係數
### 大綱
> * 1.目的
> * 2.有這些國家
> * 3.材料
> * 4.執行過程
>>  * (1)自訂義出每一波疫情(特定日期區段)
>>  * (2)做出google mobility和每日新增案例數的相關係數表格
>>  * (3)做出相關係數長條圖

## 1.目的
<img src="https://user-images.githubusercontent.com/58872054/160874930-4a8b2b1f-9f4b-49be-9f0c-4aef36a805d5.png" width=900 height=400/>
<img src="https://user-images.githubusercontent.com/58872054/160874832-c8f38bc8-0c9f-4ae4-8c09-a3e3cb018558.png" width=800 height=200/>
### 圖片來源: < https://www.dailyfxasia.com/cn/feaarticle/20170420-6015.html >

## 2.有這些國家
<img src="https://user-images.githubusercontent.com/58872054/160876447-0e080b2b-6ff8-4aec-8269-7901b8d376f5.png" width=300 height=700/>

## 3.材料
### 1. Google mobility(取自COVID-19社區人流趨勢報告)
#### Google mobility的資料所反映的是各種場所的造訪人數 (或造訪時間長度) 與基準日相比的變化。
#### 基準日代表一週內每天的「正常」值。我們是以 2020 年 1 月 3 日到 2 月 6 日這 5 週間的資料算出中位數，並以此做為基準日。
<img src="https://user-images.githubusercontent.com/58872054/160874364-4bf8a49e-6559-47bf-8bc4-2a197bdd6721.png" width=900 height=400/>

### 2. 每日新增案例數(取自Our World In Data)
#### Our world in data是由麥斯．羅瑟（Max Roser）發起的計畫所維護的網站，2010年創立於英國牛津馬丁學院。
#### 重點關注諸如貧窮，疾病，飢餓，氣候變化，戰爭，存在的風險和不平等之類的全球性大問題。
#### 原始資料來自眾多研究機構，但由團隊成員進行統整分析。網站上的資料集、敘述、圖表以及所開發的程式，都提供給任何人下載使用。網站上的文字和圖表視為著作，以創用CC公眾授權條款釋出，所有人都可自由複製改作並散布，只需標明出處。
<img src="https://user-images.githubusercontent.com/58872054/160878062-7d37a5fe-093e-4d2b-8dbf-e65af2d4fe2d.png" width=900 height=400/>

## 4.執行過程

<img src="https://user-images.githubusercontent.com/58872054/160873444-d62217fe-98b3-430f-83e6-07e6ab73a724.png" width=600 height=400/>

### 1.自訂義出每一波疫情(特定日期區段)
<img src="https://user-images.githubusercontent.com/58872054/160868265-8b486797-a525-47c7-92a0-e217eada2028.png" width=1000 height=500/>

### 2.做出google mobility和每日新增案例數的相關係數表格
#### 舉例: 澳洲
#### n為第幾波疫情，place為場所，Coefficient_of_Correlation為google mobility和每日新增案例數的相關係數，p-value為皮爾森相關係數中的p值
<img src="https://user-images.githubusercontent.com/58872054/160881546-46adbfef-bbd7-469f-9c18-e0634c6ceb96.png" width=500 height=400/>

### 3.做出相關係數長條圖
#### 顏色由淺到深代表波數增加，由這些圖可以大概知道一個國家在不同波疫情之下，google mobility和每日新增案例數的相關係數，往後有助於推論各國是否為防疫疲乏。
<img src="https://user-images.githubusercontent.com/58872054/160882016-d89eecff-a814-4f7f-8408-e583d69c094a.png" width=1000 height=500/>
<img src="https://user-images.githubusercontent.com/58872054/160882084-b55a98d7-904b-4997-9c53-7648b2ad0be7.png" width=900 height=500/>![圖片](https://user-images.githubusercontent.com/58872054/160883420-2aaead2d-bb0a-410a-8f62-14daed612f01.png)
