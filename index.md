# 進捗報告書

報告書番号 | 氏名   | 期間         | 報告日
----- | ---- | ---------- | ---
01    | 成瀬　祥馬 | 4/13 ~ 4/19 | 4/20

## 活動概要

- 研究概要

  **研究テーマ「音響解析による行動認識システムの開発」**

  - ESC-50をダウンロード
  - [ディープラーニングで音声分類(Qiita)](https://qiita.com/cvusk/items/61cdbce80785eaf28349)
    - ESC-50を使ったディープラーニングによる環境音の認識
    - ほぼ同じ内容の学習をCPU上で行っている ↓                 
    [大容量データの音声認識(CNN)をCPU上でやった作業ログ【機械学習・ディープラーニング】 ](https://trafalbad.hatenadiary.jp/entry/2019/04/29/145229)
  
  - CNNの勉強
    - **物体・画像認識と時系列データ処理入門**/チーム・カルポ著（ [Amazon](https://www.amazon.co.jp/物体・画像認識と時系列データ処理入門-チーム・カルポ/dp/4798056537) ）← 以前購入した本。CNNの基本的な部分から学べる。

- 論文調査

  - [製品開発を支える振動・音響解析技術](https://www.giho.mitsubishielectric.co.jp/giho/pdf/2019/1906113.pdf)
  
    - 音響解析と物体の振動解析を組み合わせて騒音を抑えたり、スピーカーの音質を向上させる為の技術について
    - 周波数特性上のピークレベルの低減させる＝周波数特性を広帯域に平坦化させることで、スピーカーの高音質化を実現した
    - 数値的に解析することで改善すべきポイントを明確にできる

  - [複合センサを用いた屋内環境における行動認識に関する研究](https://github.com/nakalab/progress2018/blob/SeiyaKojima/final_report/abstract_2D02.pdf)
    
    - 小島 聖哉先輩の研究論文
    - 複合センサのため、ここではミリ波センサで人の座標を検出して音源方向推定と組み合わせて音源位置を推定している。
    - マイクアレイを用いた音源方向の推定は98.7％の精度
    - マイクアレイによる音源方向の推定だけでは同じ方向に複数人いる場合に正確な識別ができない
  - [ニューラルネットワークによる実環境下での環境音認識](http://search.yahoo.co.jp/r/FOR=jGMFBK5V3iiS7jIQkUN1ghrFeasC4Udz..fmsZ5OBvxYUe5mm6_vgm2KmEPgzD5obO.ZdCRYEK7UzGCQFjfxEaIMTiJWOth1wblJy68BYclhR.7k518U0Bpn99D7.IZ5AKnANqPlav36UlEWTvbSz2XAV_rWNNIJMZ_ECVsAXx9zjgoDswQo_0Istvqtwo8zYd5t3omyUIpJb9zjys53Kva0Wz7Fbgxtg7NSzVs52NOCujBAbIFvycs_Q_RL58L2FoglyHaCXmGdoTJnlO_BlZrV7P7Q40TX7ro2wx36I1einxXXzegA2Q--/_ylt=A2Ri8EHL1pxe2jUAMhKDTwx.;_ylu=X3oDMTBtM3MwOXVkBHBvcwM0BHNlYwNzcgRzbGsDdGl0bGU-/SIG=13kjda8l2/EXP=1587437707/**https%3A//ipsj.ixsq.nii.ac.jp/ej/%3Faction=repository_uri%26item_id=181322%26file_id=1%26file_no=1)

    - MFCC（メル周波数ケプストラム係数）とパワーパターン・パワーピーク時のスペクトルの二つで実験
    - MFCCを用いて行った実験の方が識別率が高く、手動で区間検出を行ったものとHARKを用いて音源分離したものでは前者の方が識別率が高い
    - 特徴量の抽出区間が長いと入力が冗長になるため識別率に影響が及ぶ可能性がある
    - 環境音認識の速度、精度向上のための課題
      - 同一音の検出、識別
      - 音響イベントの検出、識別
      - 音区間の検出、識別
      - 音環境の検出、識別


- 進路状況

  - 本学大学院情報工学専攻　進学志望
  - 大学院入試　願書提出完了　結果待ち

- その他
  - 特になし

## 活動予定

- 研究活動
  - 論文調査（英語含め）
    - [DCASE](http://dcase.community/)
    - [ESC-50](https://github.com/karolpiczak/ESC-50)
  - MFCC([Qiitaの記事](https://qiita.com/tmtakashi_dist/items/eecb705ea48260db0b62))やSVM（サポートベクターマシン）についても調べる
  - CNNの勉強(続き)

- 振り返り事項
  - 良かった点
    - 研究テーマを決定することができた

  - 反省事項
    - 前半にまた体調を崩してしまった
    - 願書提出が結構ギリギリになってしまった
  - 今後の活動
    - まずは音から環境やシーンを推定する方法を理解する
## 研究室に来る日程と時間帯

月             | 火             | 水             | 木             | 金             | 土
------------- | ------------- | ------------- | ------------- | ------------- | -------------
- | - | - | - | - | -

### メモ
  - [アプリでリアルタイムに音環境認識（Qiita）](https://qiita.com/daisukelab/items/b47169bf688c347d087e) 以前交差点の時に見たページ
