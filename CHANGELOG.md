# Changelog

このリポジトリは、Memoria Prisma（[Memoria](https://suiryo.booth.pm/items/8758856)用の
別売りレタッチ拡張プラグイン）のバージョン確認・更新履歴の掲示専用です。
**プラグイン本体（DLL）はここには置かれません**。最新版のダウンロードは、Memoria本体と同じ
[Boothの商品ページ](https://suiryo.booth.pm/items/8758856)内のバリエーションから
行ってください（Prisma単独の商品ページはありません）。

Memoria本体のバージョン・更新履歴は別リポジトリ
（[MemoriaUpdateCheck](https://github.com/mo4ca/MemoriaUpdateCheck)）で管理しています。
Prismaは本体とは別売り・別バージョン管理のため、このリポジトリを分けています。

フォーマットは [Keep a Changelog](https://keepachangelog.com/ja/1.0.0/) に、
バージョニングは [Semantic Versioning](https://semver.org/lang/ja/) に、
（可能な限り）準拠します。

## [0.1.0] - 2026-08-28

初回リリース。

### 追加

- 明るさ・コントラスト・ハイライト・シャドウ・白レベル・黒レベルの調整
- 色温度・色被り補正・彩度によるホワイトバランス調整
- トーンカーブ（全体/R/G/B）による階調の細かい編集
- 画像全体の色・階調の偏りを自動的に検出して反映する自動補正
- 起動時のバージョン確認（このリポジトリのReleasesを参照し、新しいバージョンがあれば
  Memoria本体のウィンドウ右下にトースト通知で知らせる）
