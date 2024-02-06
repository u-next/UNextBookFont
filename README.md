# UNextBookFont

UNextBookFontは[IPAexフォント](https://moji.or.jp/ipafont/)の一部を改変した派生フォントです。


## ライセンス

当フォントはIPAexフォント同様、[IPAフォントライセンスv.1.0](https://moji.or.jp/ipafont/license/)に準拠します。
利用にあたっては同ライセンスに同意する必要があります。


## 改変内容

- hintの削除

```fonttools subset fontFileName.ttf "*" --no-hinting```

- 全角コロン（：）のvertグリフの追加

## その他

IPAexFontディレクトリは改変のされていないオリジナルのIPAexフォントであり、派生プログラムではありません。
UnextBookFont作成に利用したバージョンの参照として[IPAフォントライセンスv.1.0](https://moji.or.jp/ipafont/license/)に準拠してご利用ください。