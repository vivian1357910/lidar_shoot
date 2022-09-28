# lidar_shoot
使用LIDAR進行Unity 3D射擊模擬

本系統將在Unity 3D上呈現，以貼有QR code的紙飛機做為控制裝置，不同的QR code代表不同的物件，在Intel RealSense L515 光達深度攝影機前移動紙飛機，使用者即可操控Unity環境中的物件。

LIDAR 端：407410026 陳薇

UNITY 端：407410022 鄭友綺

指導教授：劉興民 教授


系統架構

    1.使用者操控有QR code的紙飛機
    
    2.偵測條碼與獲得座標
    
    3.傳給RealSense光達深度攝影機
    
    4.光達深度攝影機獲得資訊與實體座標
    
    5.透過TCP Server傳送給Unity端
    
    6.Unity視覺呈現給使用者
    
 



