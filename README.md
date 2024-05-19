# 目的
現在から今後における商品開発において、顧客のFeedBackの分析は欠かせない要素となる。
また、ユーザーからの感情を取得するためのデータは口コミや定量データなどが存在する。
今回は口コミデータにフォーカスを充てた分析手法について検討する

# 課題
アンケート


# NLPファンデーションモデル選定
使用するLLMモデルの選定を行う<br>
以下サイトに掲載されているPKSHAのモデルを採用する<br>
※上記モデルのファンデーションモデルはLUKE：https://qiita.com/Mizuiro__sakura/items/9ccbd655501e78df5cc6<br>
採用根拠：検索というタスクには未学習ドメインに対する対応力が必要。複数タスクによる学習により汎化性能の向上と、日本語学習データベースによる事前学習から良好な分散表現が得られると想定<br>
参考:[https://qiita.com/skillup_ai/items/ddeaa9190c2f6447ad09](https://github.com/llm-jp/awesome-japanese-llm?tab=readme-ov-file#embeddings)<br>
     https://huggingface.co/pkshatech/GLuCoSE-base-ja<br>
