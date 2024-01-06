# muscle-training

## About muscle-training
It uses a library called MediaPipe to recognize the posture of a person captured by a camera. It determines whether the arm is extended or not, and measures the number of times the arm was firmly extended and the time it was extended.
It can also be used to record training.


## How to use
### ・muscletraining.pyのファイルをダウンロード。
ダウンロードしたファイルがある環境まで移動する。

`cd (フォルダ名)`

### ・ターミナルでcondaを使えるようにする。

`conda activate`

### ・muscletraining.pyを実行する。

`python muscletraining.py`

### ・カメラに向かって腕を動かす。
この時は腰より上のみをカメラに写すようにしてください。


## 表示内容
OK or NG ：　腕がしっかり伸びていればOK、伸びていなければNGが表示される。

Count　：　腕を伸ばせていた回数を表示。

Time　：　腕が伸びていた時間を表示。一度腕を下ろさないと時間は加算されません。
