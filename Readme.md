# TextMeshProReplacer

- 既にオブジェクトに取り付けられている`UnityEngine.UI.Text`コンポーネントを`TextMeshPro`に入れ替えるEditor拡張です。

- **FontAsset名とFontファイル名は一致するようにしてください。**
  - FontAssset Creatorを使用した場合、FontAsset名が「〇〇 SDF」というファイル名になっている場合があります。

- [こちら](https://github.com/Iroha71/TextMeshProReplacer/releases/tag/Fix-TextmeshPro2)からUnityPackageをダウンロードできます。
- こちらは [jackisgames/TextMeshProReplacer](https://github.com/jackisgames/TextMeshProReplacer)をもとにしたプロジェクトになっています。
- 使い方の参考記事
  - <https://kan-kikuchi.hatenablog.com/entry/TextMeshPro_Migration>

## できないこと

- 非アクティブのオブジェクトに取り付けられているTextの入れ替え

## 未確認事項

- **Raplace All Scene**を使ったTextの入れ替え

## 確認環境

|環境名|バージョン|
|---|---|
|Unity|2021.3.8|
|TextMeshPro|3.0.6|
