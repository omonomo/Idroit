## 全角英数や半角カナが判別しやすい、文字間隔調整機能付き等幅フォント「Idroit」(Loose 版)

Copyright (c) 2025 omonomo ([https://omonomo.github.io/Idroit/](https://omonomo.github.io/Idroit/))

## 簡単な説明

自作合成フォント [Cyroit](https://omonomo.github.io/Cyroit/) に [Monoid](https://larsenwork.com/monoid/) を合成しました。

## 収録フォントの主な違い

|                              | 無印 |  EH  |  BS  |  SP  |  DG  |  FX  |  HB  |  TM  |
| ---------------------------- | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 全角スペース可視             | ss01 | ss01 |  ○  |  ○  |  ○  |  ○  |  ✕  |  ○  |
| 半角スペース可視             | ss02 | ss02 |  ✕  |  ○  |  ✕  |  ✕  |  ✕  |  ✕  |
| 3桁区切りマーク表示          | ss03 | ss03 |  ✕  |  ✕  |  ○  |  ✕  |  ✕  |  ✕  |
| 4桁区切りマーク表示          | ss04 | ss04 |  ✕  |  ✕  |  ○  |  ✕  |  ✕  |  ✕  |
| 小数小文字化                 | ss05 | ss05 |  ✕  |  ✕  |  ○  |  ✕  |  ✕  |  ✕  |
| 全角・半角形の下線           | ss06 | ss06 |  ○  |  ○  |  ○  |  ○  |  ✕  |  ○  |
| 識別性向上グリフ             | ss07 | ss07 |  ○  |  ○  |  ○  |  ○  |  ✕  |  ○  |
| DVZ のグリフ変更             | ss08 | ss08 |  ✕  |  ✕  |  ✕  |  ✕  |  ✕  |  ✕  |
| 一部罫線全角                 | ss09 | ss09 |  ✕  |  ✕  |  ✕  |  ✕  |  ✕  |  ✕  |
| スラッシュ無し0              | ss10 | ss10 |  ✕  |  ✕  |  ✕  |  ✕  |  ✕  |  ✕  |
| その他のスペース可視         | ss11 | ss11 |  ✕  |  ○  |  ✕  |  ✕  |  ✕  |  ✕  |
| 曖昧幅文字の一部半角         | ss12 | ss12 |  ✕  |  ✕  |  ✕  |  ✕  |  ✕  |  ✕  |
| 細いバックスラッシュ         | ss13 | ss13 |  ✕  |  ✕  |  ✕  |  ✕  |  ✕  |  ✕  |
| イコール2つで太字化          | ss14 | ss14 |  ✕  |  ✕  |  ✕  |  ✕  |  ✕  |  ✕  |
| 半角スペース2つ以上で可視    | ss15 | ss15 |  ✕  |  ✕  |  ✕  |  ✕  |  ✕  |  ✕  |
| ‐‑‒− に判別マーク            | ss16 | ss16 |  ✕  |  ✕  |  ✕  |  ✕  |  ✕  |  ✕  |
| cosvwxz に判別マーク         | ss17 | ss17 |  ✕  |  ✕  |  ✕  |  ✕  |  ✕  |  ✕  |
| アロー、パイプラインリガチャ | ss18 | ss18 |  ✕  |  ✕  |  ✕  |  ✕  |  ✕  |  ✕  |
| スラッシュ0                  | ss19 | ss19 |  ✕  |  ✕  |  ✕  |  ✕  |  ✕  |  ✕  |
| 中立・曖昧幅文字半角         |  ✕  |  ✕  |  ✕  |  ✕  |  ✕  |  ✕  |  ✕  |  ○  |
| 少ない絵文字                 |  ✕  |  ○  |  ✕  |  ✕  |  ✕  |  ✕  |  ✕  |  ✕  |
| カーニング機能               |  ○  |  ○  |  ○  |  ○  |  ○  |  ✕  |  ○  |  ○  |
| Nerd Fonts                   |  ○  |  ○  |  ○  |  ○  |  ○  |  ○  |  ○  |  ○  |

**無印**: 通常版 (GSUB の ss フィーチャにて機能の ON/OFF が可能)  
**EH**: 絵文字減らした版 (GSUB の ss フィーチャにて機能の ON/OFF が可能)  
**BS**: 基本版  
**SP**: スペシャルスペース版  
**DG**: 桁区切り表示版  
**FX**: 文字間隔固定版  
**HB**: 平凡版  
**TM**: ターミナル版  

※ LG 付きはリガチャ対応

## 通常版、絵文字減らした版の異体字設定

|      | 説明                           |      | 説明             |
| :--: | ------------------------------ | :--: | ---------------- |
| cv01 | 可視全角スペース               | cv44 | ストローク付きD  |
| cv02 | 可視半角スペース               | cv62 | セリフ付きV      |
| cv03 | 可視ノーブレークスペース       | cv66 | ストローク付きZ  |
| cv10 | ドットなし0                    | cv72 | マーク付きb      |
| cv11 | リガチャ<-                     | cv73 | マーク付きc      |
| cv12 | リガチャ->                     | cv74 | マーク付きd      |
| cv13 | リガチャ<->                    | cv77 | マーク付きg      |
| cv19 | スラッシュ0                    | cv81 | マーク付きk      |
| cv21 | リガチャ<=                     | cv85 | マーク付きo      |
| cv22 | リガチャ=>                     | cv86 | マーク付きp      |
| cv23 | リガチャ<=>                    | cv87 | マーク付きq      |
| cv25 | 実線分数スラッシュ             | cv89 | マーク付きs      |
| cv26 | 実線縦棒                       | cv91 | マーク付きu      |
| cv27 | 実線enダッシュ                 | cv92 | マーク付きv      |
| cv28 | 実線emダッシュ                 | cv93 | マーク付きw      |
| cv31 | リガチャ<\|                    | cv94 | マーク付きx      |
| cv32 | リガチャ\|>                    | cv95 | マーク付きy      |
| cv35 | マーク付きハイフン             | cv96 | マーク付きz      |
| cv36 | マーク付きノーブレークハイフン | cv99 | マーク付きヘベペ |
| cv37 | マーク付きフィギュアダッシュ   |      |                  |
| cv38 | マーク付きマイナスサイン       |      |                  |

## 素材にさせていただいたフォントからの変更内容

- em 値やラインギャップの変更
- サイズや縦横比、ウェイトの変更
- オブリーク体の新規生成
- 一部のグリフについて座標や形状、文字幅 (全角・半角) の変更
- 各グリフを素材とした新規グリフの追加
- 他の素材フォントと競合するグリフの削除
- 絵文字減らした版については、絵文字の削除 (基本ラテン文字等は除く)
- OpenType フィーチャの削除、追加

## 素材にさせていただいたフォント

[Monoid (Version 0.61)]  
Copyright (c) 2016, Andreas Larsen  
([https://larsenwork.com/monoid/](https://larsenwork.com/monoid/))  
主にラテン文字、ギリシア文字、キリル文字で使用しています。Monoid は [The MIT License と SIL Open Font License v1.1](https://github.com/larsenwork/monoid/#license) のデュアルライセンスです。

[Inconsolata (Version 3.001)]  
Copyright 2006 The Inconsolata Project Authors  
([https://levien.com/type/myfonts/inconsolata.html](https://levien.com/type/myfonts/inconsolata.html))  
主に Monoid に含まれない文字の補完で使用しています。Inconsolata のライセンスは [SIL Open Font License v1.1](https://github.com/google/fonts/blob/main/ofl/inconsolata/OFL.txt) です。

[Circle M+ (Version 1.063a)]  
Copyright(c) 2020 M+ FONTS PROJECT, itouhiro  
([https://itouhiro.github.io/mixfont-mplus-ipa/](https://itouhiro.github.io/mixfont-mplus-ipa/))  
主に仮名文字で使用しています。Circle M+ のライセンスは [M+ Font License](https://itouhiro.github.io/mixfont-mplus-ipa/mplus/LICENSE_E.txt) です。

[BIZ UDゴシック (Version 1.051)]  
Copyright 2022 The BIZ UDGothic Project Authors  
([https://github.com/googlefonts/morisawa-biz-ud-gothic](https://github.com/googlefonts/morisawa-biz-ud-gothic))  
主に漢字で使用しています。BIZ UDゴシック のライセンスは [SIL Open Font License v1.1](https://github.com/googlefonts/morisawa-biz-ud-gothic/blob/main/OFL.txt) です。

[NINJAL 変体仮名フォント (Ver.1.01)]
Copyright(c) National Institute for Japanese Language and Linguistics (NINJAL), 2018.  
([https://cid.ninjal.ac.jp/kana/font/](https://cid.ninjal.ac.jp/kana/font/))  
変体仮名で使用しています。NINJAL 変体仮名フォントのライセンスは [Apache Lincense v2.0](https://cid.ninjal.ac.jp/kana/font/) です。

[Symbols Nerd Font (Version 001.000;Nerd Fonts 3.5.1)]  
Copyright (c) 2016, Ryan McIntyre  
([https://www.nerdfonts.com](https://www.nerdfonts.com))  
サイズを調整して使用しています。Symbols Nerd Font のライセンスは [SIL Open Font License v1.1](https://github.com/google/fonts/blob/main/ofl/inconsolata/OFL.txt) (生成スクリプトのライセンスは [The MIT License](https://github.com/ryanoasis/nerd-fonts/blob/master/patched-fonts/NerdFontsSymbolsOnly/LICENSE)) です。

## Idroit のライセンス

[SIL Open Font License Version 1.1](https://github.com/omonomo/Idroit/blob/main/build/IdroitLoose/OFL.txt)

## 謝辞

Idroit の合成、製作にあたり、素晴らしいフォントやツール類を提供してくださっております製作者の方々に感謝いたします。
