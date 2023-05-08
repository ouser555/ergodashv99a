# ergodashv99a

## 20230409更新說明

* 20230509-qmk firmware-0.20.4
  * 原始檔  
    https://github.com/ouser555/ergodashv99a/tree/main/firmware/ergodash
    
    ```  
    make ergodash/rev3:v99v5
    ```  
    
  * 燒錄檔  
    https://github.com/ouser555/ergodashv99a/blob/main/hex/ergodash_rev3_v99v5.hex
    
  * VIA config檔  
    https://github.com/ouser555/ergodashv99a/blob/main/via%20configurator/ErgoDash_4key_2u_inner%20-remapt03.json
  
* 版本特點
  * 修正電腦關機後再開鍵盤連線會不正常的問題
  
  * 電腦休眠時RGB自動關閉
  
  * 支援VIA configurator 3.0.0
    建議使用者自己保存一份此版本的安裝檔，防止有一天官方不再提供。
  
  * VIA RGB亮度拖動範圍限制在150以下，防止電流過載
  
* VIA使用注意事項
  * 目前使用VIA 3.0版，安裝版或網頁版皆可。
  
  * 網頁版會一隨著版本更新保持在最新版本，如果有一天網頁版突然無法使用，可能是更新導致的。

  * 安裝版在鍵盤重新插拔USB時會無法與VIA連線，雖然config檔有保存在VIA軟體內，但是會辨識不到鍵盤，
    此時要重新load一次config檔即可再度辨識。每一次都一樣
