## 全角英数や半角カナが判別しやすい、文字間隔調整機能付き等幅フォント「Meroit」(Loose 版)

Copyright (c) 2024 omonomo ([https://omonomo.github.io/Meroit/](https://omonomo.github.io/Meroit/))

## 簡単な説明

自作フォント [Cyroit](https://omonomo.github.io/Cyroit/) に Meslo LG を合成しました。Cyroit の姉妹フォントになります。

## 収録フォントの主な違い

|                     | 無印 |  EH  | BS  | SP  | DG  | FX  | HB  |
| ------------------- | :--: | :--: | :-: | :-: | :-: | :-: | :-: |
| 全角スペース可視    | ss01 | ss01 |  ○  |  ○  |  ○  |  ○  |  ✕  |
| 半角スペース可視    | ss02 | ss02 |  ✕  |  ○  |  ✕  |  ✕  |  ✕  |
| 3桁区切りマーク表示 | ss03 | ss03 |  ✕  |  ✕  |  ○  |  ✕  |  ✕  |
| 4桁区切りマーク表示 | ss04 | ss04 |  ✕  |  ✕  |  ○  |  ✕  |  ✕  |
| 小数小文字化        | ss05 | ss05 |  ✕  |  ✕  |  ○  |  ✕  |  ✕  |
| 全角・半角形の下線  | ss06 | ss06 |  ○  |  ○  |  ○  |  ○  |  ✕  |
| 識別性向上グリフ    | ss07 | ss07 |  ○  |  ○  |  ○  |  ○  |  ✕  |
| DQVZ のグリフ変更   | ss08 | ss08 |  ✕  |  ✕  |  ✕  |  ✕  |  ✕  |
| 一部罫線全角        | ss09 | ss09 |  ✕  |  ✕  |  ✕  |  ✕  |  ✕  |
| スラッシュ無し0     | ss10 | ss10 |  ✕  |  ✕  |  ✕  |  ✕  |  ✕  |
| 少ない絵文字        |  ✕   |  ○   |  ✕  |  ✕  |  ✕  |  ✕  |  ✕  |
| カーニング機能      |  ○   |  ○   |  ○  |  ○  |  ○  |  ✕  |  ○  |
| Nerd Fonts          |  ○   |  ○   |  ○  |  ○  |  ○  |  ○  |  ○  |

**無印**: 通常版 (GSUB の ss フィーチャにて機能の ON/OFF が可能)  
**EH**: 絵文字減らした版 (GSUB の ss フィーチャにて機能の ON/OFF が可能)  
**BS**: 基本版  
**SP**: スペシャルスペース版  
**DG**: 桁区切り表示版  
**FX**: 文字間隔固定版  
**HB**: 平凡版

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

[Meslo LG (1.210)]  
Copyright 2009, 2010, 2013 André Berg  
([https://github.com/andreberg/Meslo-Font](https://github.com/andreberg/Meslo-Font))  
主にラテン文字、ギリシア文字、キリル文字で使用しています。Meslo LG のライセンスは [Apache Lincense v2.0](https://www.apache.org/licenses/LICENSE-2.0) です。

[Inconsolata (Version 3.001)]  
Copyright 2006 The Inconsolata Project Authors  
([https://levien.com/type/myfonts/inconsolata.html](https://levien.com/type/myfonts/inconsolata.html))  
主に Meslo LG に含まれないラテン文字で使用しています。Inconsolata のライセンスは [SIL Open Font License v1.1](http://scripts.sil.org/ofl) です。

[Circle M+ (Version 1.063a)]  
Copyright(c) 2020 M+ FONTS PROJECT, itouhiro  
([https://itouhiro.github.io/mixfont-mplus-ipa/](https://itouhiro.github.io/mixfont-mplus-ipa/))  
主に仮名文字で使用しています。Circle M+ のライセンスは [M+ Font License](https://itouhiro.github.io/mixfont-mplus-ipa/mplus/LICENSE_E.txt) です。

[BIZ UDゴシック (Version 1.051)]  
Copyright 2022 The BIZ UDGothic Project Authors  
([https://github.com/googlefonts/morisawa-biz-ud-gothic](https://github.com/googlefonts/morisawa-biz-ud-gothic))  
主に漢字で使用しています。BIZ UDゴシック のライセンスは [SIL Open Font License v1.1](http://scripts.sil.org/ofl) です。

[NINJAL 変体仮名フォント (Ver.1.01)]
Copyright(c) National Institute for Japanese Language and Linguistics (NINJAL), 2018.  
([https://cid.ninjal.ac.jp/kana/font/](https://cid.ninjal.ac.jp/kana/font/))  
変体仮名で使用しています。NINJAL 変体仮名フォントのライセンスは [Apache Lincense v2.0](https://www.apache.org/licenses/LICENSE-2.0) です。

[Symbols Nerd Font (Version 001.000;Nerd Fonts 3.2.1)]  
Copyright (c) 2016, Ryan McIntyre  
([https://www.nerdfonts.com](https://www.nerdfonts.com))  
サイズを調整して使用しています。Symbols Nerd Font のライセンスは [SIL Open Font License v1.1](http://scripts.sil.org/ofl) です。

## Meroit のライセンス

SIL Open Font License Version 1.1  
([http://scripts.sil.org/ofl](http://scripts.sil.org/ofl))

## 謝辞

Meroit の合成、製作にあたり、素晴らしいフォントやツール類を提供してくださっております製作者の方々に感謝いたします。