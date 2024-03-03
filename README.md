# Animal Population Prediction

Python 動物族群預測

## 設計理念
本專題主要是用線性代數的方法探討動物族群隨時間推進，在數量上會呈現甚麼變化，主要探討的面向:  
  1.動物繁衍對族群結構的影響  
  2.動物遷徙對棲息地分布的影響  
藉由以上2個面向的有一定研究後，製作出一套工具方便使用者能夠預測和估計動物數量，讓研究人員有一個好的預估模型和簡單的工具可以幫助研究。

## 成果
<img width="377" alt="image" src="https://github.com/Lowen0909/Animal-Population-Prediction/assets/82707190/c639de3d-8556-4909-8b63-37b5c0ddd319">  
<img width="379" alt="image" src="https://github.com/Lowen0909/Animal-Population-Prediction/assets/82707190/76fa602f-2c8e-4404-8a85-6508f7314941">

## 數學模型
### 1.生殖預測:使用Leslie模型(P為動物數量、pi為存活率、fj為出生率)  
<img width="470" alt="image" src="https://github.com/Lowen0909/Animal-Population-Prediction/assets/82707190/b58c0518-8aac-4a18-abd5-97db867181fe">  

### 2.遷徙預測:Markov模型
An、Bn代表當下兩地動物分布, ps、p′s為動物滯留當地的比例, pl、p′l為離開當地的比例,An+1、Bn+1為預測的分布。  
<img width="317" alt="image" src="https://github.com/Lowen0909/Animal-Population-Prediction/assets/82707190/4b240564-cebc-4a24-b535-e9cbfdb745f4">

