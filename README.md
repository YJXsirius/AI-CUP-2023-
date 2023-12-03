安裝環境：
    1. 使用 [Anaconda](https://www.anaconda.com/download) 安裝 `Jupyter Notebook2.x`
    2. 安裝 `tensorFlow-GPU 2.9.1` 以及 `CUDA 11.2` `Cudnn 8.1.0` 
    3. 使用指令 `conda install --file requirements.txt` 來安裝所需套件

資料前處理：
    1.通過鏈接下載訓練與驗證資料:  https://drive.google.com/drive/folders/1UdS1-7mrsmyBLdsly0COI_6Br1utyh5p?usp=drive_link
    2.將下載的CSVs文件夾存放在根目錄,取代原先的CSVs文件夾
    3.



檔案介紹:
     Dan模型訓練程式:  Dan Training Tutorial-resred+rnn+分段式訓練(adam)(batch_size=1024)(打乱顺序)30000數據生成器-上傳.ipynb
     Kyu模型訓練程式:  Kyu_Training_Tutorial_resred+分段式訓練(adam)(batch_size=1024)(打乱顺序)30000數據生成器-上傳.ipynb
     PlayStyle模型訓練程式:  PlayStyle Training_va0.740(image_v3.3,EfficientNetB6,數據增強.ipynb
     PlayStyle所使用的圖片生成器:  PSimage_v3.3.ipynb