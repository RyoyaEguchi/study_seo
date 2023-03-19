# SEO について学習したメモ

## SEO って何？

Search Engine Optimization：検索エンジン最適化　のこと
通常、SEO といえば Google の検索エンジン対策を指す

## SEO の大前提

Google 検索は「**Q&A システム**」

- ユーザーの「Q」に対して良質な「A」を返したい
- SEO ができていても、中身のないサイトにはペナルティがつけられ排除される
- 基本的な SEO 対策のみで OK

→ SEO は**Google の立場に立って考える**ことが重要

## 検索順位の決まり方

[Google 検索の基本事項](https://developers.google.com/search/docs/essentials?hl=ja)というガイドラインがある
　 → このガイドラインに準拠して対策を行う

### Google 検索の基本事項の要約

- サイトは・・・

  - Google がページの存在や構成を認識しやすいようにする
  - Google がページ内容を理解しやすいようにソースを記述する
  - 訪問者の利便性を第一に考えてコンテンツを作成する
  - 他サイトのコピーではなく、独自の情報を提供する
  - Google や訪問者を欺くような小細工で順位を上げようとしない

- よって、SEO 施策の種類は下記の 3 つ！
  - サイト設計
  - コンテンツ作成
  - 被リンク獲得

#### サイト設計について

クローラビリティとユーザビリティを意識して行う

- **クローラビリティの高いサイト**にする
  - クローラーがサイト内を巡回しやすいように、また内容を把握しやすいように設計する
- **ユーザビリティの高いサイト**にする
  - 訪問者が欲しい情報をスムーズに取得できるように設計する

#### コンテンツ作成について

ユーザビリティを第一において行う

- コンテンツを充実させる
  - 充実したコンテンツとは、ページの内容が他よりも充実しており、情報に独自性があるもの
- 充実したコンテンツが多くあると、サイト自体の評価が上がる
  - **ドメインパワーが強いサイト**という
  - そのサイトに属するページは、そのサイトのドメインパワーを引き継ぐので優先的に上位表示される

つまり、検索順位は
　　ページの充実度 + ドメインパワー
を競合サイトと相対的に比較して決まる

#### 被リンク獲得について

- 被リンクとは
  - 外部サイトから自サイトに向けたリンクのこと
  - 被リンクを意図的に増やすと**ペナルティの対象**となる
- 被リンクの質
  - 評価の高いサイト（ドメインパワーの強いサイト）かつ、関連性の高いサイトから貼られると評価が高い
  - 逆に、評価の低いサイト、関連性の低いサイトからのリンクは評価されない
- 被リンク営業を行うところも
  - 特集記事を書いて営業先のサイトにリンクを貼る見返りに、相手のサイトにも自サイトのリンクを貼ってもらうことで被リンクを獲得する手法

## 2023 以降の SEO の要点

- 被リンク
  - 量より質
- 文字数
  - 文字数を意識する必要はない
- コンテンツ形式
  - 基本的に文章だが、図や画像・動画を用いてユーザーにわかりやすくする
- Google アルゴリズム
  - Google の定めるガイドラインに準拠する
  - 検索アルゴリズムを過度に意識する必要はない
- E-E-A-T を表現する
  - 経験性-専門性-権威性-信頼性
  - Google ではなく、あくまでもユーザーに対するサービスクオリティの向上を意識して行う
- コアウェブバイタルを良好に
  - [PageSpeed Insights](https://pagespeed.web.dev/?hl=ja)でサイトを分析し、数値を改善する

## 上位表示するまでにかかる日数

キーワードの難易度にもよるが、本来の順位が確定するまでに、新規のページを作成して検索エンジンにインデックスされてから**1~3 ヶ月程度**の時間がかかる

本来の順位が確定した後も、下記の指標に基づいて順位変動する

- クリック率
  - クリックされた回数 / 検索結果に表示された回数
- ページ滞在時間
- 直帰率
  - ユーザーがそのページからサイト内の他のページに移動せず、検索画面に直帰する確率
- ページ内容の陳腐化
  - 時間の経過でページ内容が古くなる

## ビジネス向けSEO

リアルビジネス用SEOとオンラインビジネス用SEOがある

難易度で言うと、
　　リアルビジネス用 SEO < オンラインビジネス用 SEO

リアルビジネスとオンラインビジネスを表にまとめると、下記のようになる

|           | リアルビジネス                      | オンラインビジネス   |
| --------- | ----------------------------------- | -------------------- |
| 対象      | 小企業<br>個人事業主<br>他          | アフィリエイト<br>他 |
| 必要な PV | 2000~3000PV(小規模なリアルビジネス)<br>多すぎるとキャパオーバーになることも | 数万~数十万 PV<br>いくら多くなってもキャパオーバーにはならない      |
|           |                                     |                      |


## SEOで使えるツール

- Googleのツール
  - Search Console
  - Googleアナリティクス
- ツール
  - [キーワード抽出](https://related-keywords.com/)
  - [キーワード検索ボリューム](http://www.aramakijake.jp/)

## キーワードとは

SEOを始める前に、**キーワード選定**が必要
→ どのキーワードで検索された時に上位に表示させたいかを選ぶ

### キーワードの種類

- ビッグキーワード
  - 検索語句が1語
    - SEO
- ミドルキーワード
  - 検索語句が2語
    - SEO やり方
- スモールキーワード（ロングテールキーワード）
  - 検索語句が3語以上
    - SEO やり方 初心者
    - SEO やり方 index 初心者
- トレンドキーワード
  - 突然検索ニーズが伸びた語句
    - 流行が過ぎるとすぐにアクセスが減る危険もある
  - いち早く察知することで、競合に対して優位に立てる場面も
  - 「Yahoo! リアルタイム検索」や「Googleトレンド」を用いて見つける


[実践編](./実践メモ.md)に続く