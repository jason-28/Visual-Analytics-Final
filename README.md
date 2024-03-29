# 假新聞輿論之影響

* 由於近幾年假新聞的議題水漲船高，我們這組使用Kaggle裡所提供的中國假新聞資料與現行的台灣新聞資料進行比對及研究。

## 內容簡介

### 資料集介紹:

**中國假新聞**:來源為Kaggle，由WSDM舉辦的假新聞資料競賽。

**台灣新聞**:來源為台視(TTV)、ETToday新聞雲、EpochTime大紀元。

* 使用Google翻譯成繁體中文，並使用Jieba進行斷詞並提取基本特徵(長度、詞數、問號、驚嘆號)，再對以上兩個資料集做標題、詞語數量長度的分析。

### 字詞分析:

* 將文章的字詞作分析，製作出文字雲及字詞熱門程度排行的長條圖。

* 使用SAS Viya對10個熱門字詞所延伸出去的字詞作關聯程度的分析，並探討其中字詞與假新聞之間的關聯。

### 情感分析:

* 使用NTU及元智大學的情感詞庫對以上兩個資料集作情感分析

* 延伸討論中國假新聞的情感態度、背後目的及台灣民眾大多透過新聞得到的情感取向。

## [網址]( https://darrenlucreate.github.io/Fake-News)

## 參考資料

http://blog.pulipuli.info/2017/11/fasttag-identify-part-of-speech-in.html
