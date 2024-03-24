# Attention-CNN-LSTM

注意機構を組み込んだLSTMとCNNを組み合わせたEncoder-Decoderモデル。

データのインターバルは日次であり、次ステップの回帰モデルとして構築した。

以下の論文を参考にした。
[A CNN-STLSTM-AM model for forecasting USD/RMB exchange rate](https://www.sciencedirect.com/science/article/pii/S2307187723000809)

※論文元の画像からLag-model(予測が1ステップ前の実データと連動してしまう現象)が発生しているため、実際には予測モデルとは言えないと考えられる。

![image](https://github.com/Yuhei-Handa/Attention_CNN_LSTM/assets/135846516/8383275e-23a7-448d-8d5b-46ab81dab430)
