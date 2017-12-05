## 確定Shiny APP可以運行

參考文件 [link](https://paper.dropbox.com/doc/ShinyAPP-QmAymlUAYl4WJmr8dQw0R?_tk=share_copylink)   






## No such file or directory  
### 問題  
Warning in file(file, "rt") :
  無法開啟檔案 'usedcar1209.csv' ：No such file or directory
Warning: Error in file: 無法開啟連結
### 解法  

將 path 重設
```
#Path Example(Mac): '/Users/kristen/Desktop/Azureml-shiny-app-master/Shiny_Titanic'
#Path Example(Windows): 'C:/Users/kristen/Desktop/Azureml-shiny-app-master/Shiny_Titanic'
or 'C:\Users\kristen\Desktop\Azureml-shiny-app-master\Shiny_Titanic'
```
