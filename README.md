# text-to-speak
tts_colab.ipynbは、事前にマウントしたxtts_v2_model.pthに指定されたwavファイルを追加学習させ、音声合成を行うファイルです。  
尚、このバージョンは英語で事前学習を行っているため(正確には日本語も学習してはいるが)、生成することのできるmessageは英語のみである。(cutletとか入れて日本語生成できるように精進いたします。)
# Usage
OneDrive内のxtts_v2_model.pthをGoogleDrive/マイドライブ内に移動させる。  
google colabでtts_colab.ipynbを開く。  
colab内のディスクドライブに学習させたいwavファイルをアップロードする。(ノイズが少なく、なるべく鮮明な30秒ほどの音声が望ましい) 

---
![スクリーンショット 2024-06-21 205914](https://github.com/Watayu-silicon/text-to-speak/assets/105160299/2b8aa82d-753f-4d32-a534-d726d80e5dda)
---

tts_colab.ipynb内のコードを順に実行していくと、ディスクドライブ内にoutput.wavが作成され、ダウンロードして聞くことができる。
