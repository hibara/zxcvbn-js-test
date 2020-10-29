# zxcvbn-js-test

このレポジトリは、オンラインストレージサービスを提供している Dropbox が開発、実際に使用している「パスワード強度推定ツール」 `zxcvbn.js` を使ったサンプルコードです。実際、パスワード文字列を評価した強度推定「結果」が、どういった項目を返すかを確認することができます。HTML5 + CSS3 + JavaScript で書かれており、ちなみにjQueryなどの他のライブラリは一切使っておりません。

また、ここにアップロードされているサンプルを解説している記事を以下に投稿しました。

***パスワード強度推定メーター（zxcvbn.js）を実装してみる***  
<https://qiita.com/hibara/items/fbd26704b8ab7fd74fb1>

こちらの解説を読み進めながら、サンプルコードを見ると、より理解が深まるかと思います。

## 動作確認ページ

実際に動作確認できるページを用意しました。こちらからどうぞ。  
<https://hibara.github.io/zxcvbn-js-test/>

## zxcvbn.js の入手場所

ここで使われているパスワード強度推定ツール `zxcvbn.js` は、このレポジトリからでもダウンロード可能ですが、最新版（正式版）は以下の公式レポジトリから入手することができます。

以下はそのレポジトリです。

dropbox/zxcvbn - GitHub  
<https://github.com/dropbox/zxcvbn>

JSファイルだけであるのなら、こちらからmapファイルも含めてダウンロードできます。  
<https://github.com/dropbox/zxcvbn/tree/master/dist>

## zxcvbn のコンセプト、設計思想

実際、zxcvbn が、どのような仕様で、つまりどういった設計思想の元に開発されているかは、以下のブログ記事から読むことができます。2012年時点での記事ですが、他のウェブサービスとも比較して、「強度」「推定」計算の指針が大きくちがうことが示されています。

<https://blogs.dropbox.com/tech/2012/04/zxcvbn-realistic-password-strength-estimation/>

英語を読むのがシンドイという方は、一応拙訳ですが、Qiitaに日本語訳の記事を投稿しています。

***Dropbox開発のzxcvbn（パスワード強度メーター）のブログ記事を全訳してみた***  
<https://qiita.com/hibara/items/37ba7a1f8ba2d54ae600>

## ライセンス

MITライセンス

## お問い合わせ

基本的には無保証・サポートはありませんが、もし万が一、提案・要望・ご意見などありましたら、Issues に追加いただくか、以下までご連絡ください。できる範囲で対応いたします。

Mituhiro Hibara  
<mailto:m@hibara.org>
