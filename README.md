# ラフカ語 同語根語生成器

[ブラウザーで使う](https://jinubbbo5454-rgb.github.io/lafca-word-generator/)

アルディア語の入力から、登録されたラフカ語の同語根語と、実装済みの音変化規則に基づく新語候補を表示します。登録形・関連形・候補・保留を区別し、候補の採用や実在は確定しません。

`index.html` をダウンロードしてブラウザーで開くと、オフラインでも使えます。CSS・JavaScript・照合データを含む単独HTMLで、外部ライブラリや通信は不要です。

## 語彙と更新

語彙の唯一の正本は [ウェブラフカ語辞書](https://jinubbbo5454-rgb.github.io/lafca-dictionary/) の [dictionary.json](https://github.com/jinubbbo5454-rgb/lafca-dictionary/blob/main/dictionary.json) です。この生成器にはビルド時点の照合データを埋め込んでいます。辞書の変更は再ビルド・再公開後に反映されます。

このリポジトリは配布用です。元の作業環境の `語彙生成器/build.py` で再生成し、検査後に `語彙生成器/export_pages.py` で配布物を更新します。配布HTML内の語彙を独立した辞書として編集しないでください。

GitHub Pages は `main` ブランチのルートから公開します。
