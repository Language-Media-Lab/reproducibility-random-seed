# 書誌情報
竹下昌志, ジェプカラファウ, 荒木健治, (2022), NLPモデルの性能の再現可能な測定に向けて:再現性の時間軸モデルと日本のNLP研究の再現性の簡易的調査, 言語処理学会第28回年次大会(NLP2022)

# RS値によるランダム性
[RS_livdoor.ipynb](https://github.com/Language-Media-Lab/reproducibility-random-seed/blob/main/RS_livdoor.ipynb)に実装コードを載せています。
最初のセルで、google colabで動かすために必要なライブラリをインストールしていますが、これは環境に合わせて適宜修正・追加等してください。

[scores](https://github.com/Language-Media-Lab/reproducibility-random-seed/tree/main/scores)に各モデルのスコアの結果を載せています。pklファイルになっているため、pickle等で読み込むことができます。

本実験で使用しているコードは『BERTによる自然言語処理入門』を参考にしています。
- 本: https://www.ohmsha.co.jp/book/9784274227264/
- github: https://github.com/stockmarkteam/bert-book
