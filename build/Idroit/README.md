## 全角英数や半角カナが判別しやすい、文字間隔調整機能付き等幅フォント「Idroit」

Copyright (c) 2025 omonomo ([https://omonomo.github.io/Idroit/](https://omonomo.github.io/Idroit/))

## 簡単な説明

自作合成フォント [Cyroit](https://omonomo.github.io/Cyroit/) に [Monoid](https://larsenwork.com/monoid/) を合成しました。

## 収録フォントの主な違い

|                      | 無印 |  EH  |  BS  |  SP  |  DG  |  FX  |  HB  |
| -------------------- | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 全角スペース可視     | ss01 | ss01 |  ○  |  ○  |  ○  |  ○  |  ✕  |
| 半角スペース可視     | ss02 | ss02 |  ✕  |  ○  |  ✕  |  ✕  |  ✕  |
| 3桁区切りマーク表示  | ss03 | ss03 |  ✕  |  ✕  |  ○  |  ✕  |  ✕  |
| 4桁区切りマーク表示  | ss04 | ss04 |  ✕  |  ✕  |  ○  |  ✕  |  ✕  |
| 小数小文字化         | ss05 | ss05 |  ✕  |  ✕  |  ○  |  ✕  |  ✕  |
| 全角・半角形の下線   | ss06 | ss06 |  ○  |  ○  |  ○  |  ○  |  ✕  |
| 識別性向上グリフ     | ss07 | ss07 |  ○  |  ○  |  ○  |  ○  |  ✕  |
| DQVZ のグリフ変更    | ss08 | ss08 |  ✕  |  ✕  |  ✕  |  ✕  |  ✕  |
| 一部罫線全角         | ss09 | ss09 |  ✕  |  ✕  |  ✕  |  ✕  |  ✕  |
| ドット無し0          | ss10 | ss10 |  ✕  |  ✕  |  ✕  |  ✕  |  ✕  |
| その他のスペース可視 | ss11 | ss11 |  ✕  |  ✕  |  ✕  |  ✕  |  ✕  |
| 少ない絵文字         |  ✕  |  ○  |  ✕  |  ✕  |  ✕  |  ✕  |  ✕  |
| カーニング機能       |  ○  |  ○  |  ○  |  ○  |  ○  |  ✕  |  ○  |
| Nerd Fonts           |  ○  |  ○  |  ○  |  ○  |  ○  |  ○  |  ○  |

**無印**: 通常版 (GSUB の ss フィーチャにて機能の ON/OFF が可能)  
**EH**: 絵文字減らした版 (GSUB の ss フィーチャにて機能の ON/OFF が可能)  
**BS**: 基本版  
**SP**: スペシャルスペース版  
**DG**: 桁区切り表示版  
**FX**: 文字間隔固定版  
**HB**: 平凡版

※ LG 付きはリガチャ対応

## 素材にさせていただいたフォントからの変更内容

- em 値やラインギャップの変更
- サイズや縦横比、ウェイトの変更
- オブリーク体の新規生成
- 一部のグリフについて座標や形状、文字幅 (全角・半角) の変更
- 各グリフを素材とした新規グリフの追加
- 他の素材フォントと競合するグリフの削除
- 絵文字減らした版については、基本ラテン文字以外の絵文字の削除
- OpenType フィーチャの削除、追加

## 素材にさせていただいたフォント

[Monoid (Version 0.61)]  
Copyright (c) 2016, Andreas Larsen  
([https://larsenwork.com/monoid/](https://larsenwork.com/monoid/))  
主にラテン文字、ギリシア文字、キリル文字で使用しています。Monoid は [The MIT License と SIL Open Font License v1.1](https://github.com/larsenwork/monoid/#license) のデュアルライセンスです。

[Inconsolata (Version 3.001)]  
Copyright 2006 The Inconsolata Project Authors  
([https://levien.com/type/myfonts/inconsolata.html](https://levien.com/type/myfonts/inconsolata.html))  
主に Monoid に含まれない文字で使用しています。Inconsolata のライセンスは [SIL Open Font License v1.1](https://github.com/google/fonts/blob/main/ofl/inconsolata/OFL.txt) です。

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

[Symbols Nerd Font (Version 001.000;Nerd Fonts 3.4.0)]  
Copyright (c) 2016, Ryan McIntyre  
([https://www.nerdfonts.com](https://www.nerdfonts.com))  
サイズを調整して使用しています。Symbols Nerd Font のライセンスは [SIL Open Font License v1.1](https://github.com/google/fonts/blob/main/ofl/inconsolata/OFL.txt) (生成スクリプトのライセンスは [The MIT License](https://github.com/ryanoasis/nerd-fonts/blob/master/patched-fonts/NerdFontsSymbolsOnly/LICENSE)) です。

## Idroit のライセンス

[SIL Open Font License Version 1.1](https://github.com/omonomo/Idroit/blob/main/build/Idroit/OFL.txt)

## 謝辞

Idroit の合成、製作にあたり、素晴らしいフォントやツール類を提供してくださっております製作者の方々に感謝いたします。
