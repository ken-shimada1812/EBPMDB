---
id:
title: "住宅価格の変動"
description: "アメリカにおいて住宅価格に起因する所有資産の変動が出生率に与える影響"
date: "2024-05-19"
category: "fertility"
categoryLabel: "少子化対策"
tables:
  [
    {
      "title": "住宅を所有する世帯の出生率",
      "effectiveness": "効果あり",
      "strength": 3
    },
    {
      "title": "賃貸住宅に居住する世帯の出生率",
      "effectiveness": "効果なし",
      "strength": 3
    }
  ]
points:
  - 住宅を所有する世帯では、住宅価格が上昇すると出生率が上昇する。
  - 賃貸住宅に居住する世帯では、住宅価格の変動による出生率への変化は見られない。
  - 住宅を所有する世帯のうち、低所得や子供がいない世帯に関しては、住宅価格の変動による出生率への影響は見られない。

contacts:
   - 石井俊輔 (The University of Edinburgh)
---

## 背景
- 理論的には世帯収入が上がると出生率も上がると考えられるが、実際両者の間には負の相関関係が示されている。
- 米国では、住宅価格が高い州において出生率は低い傾向がある。
- 因果関係に迫ったいくつかの研究では、収入が減少した時に出生率が減少することが示されているが、一般化可能性など分析の課題がある。

## 介入
- 住宅価格の変動による世帯が保有している資産額の変化

## 評価指標
- 出生率: 四半期ごとの15-44歳の女性1000人当たりの出生数。

## 分析方法
- 地域や年の固定効果を加えた線形確率モデルによる推定。

## 証拠の強さ
- SMS: 3
  - 出生率が所有資産額の変化ではなく、マクロ経済の動向の影響を受けている可能性がある。これに対して、失業率や一人当たり実質所得をコントロール変数としている。同様の分析を賃貸住宅に住む世帯でも行い、マクロ経済状況が分析に影響を与えていないことを確認している。
  - 住宅価格の変動に地域差があるため、出産前の女性がこれから住宅価格が上昇しそうな地域に移住する可能性があり、その場合推定値に過大推定のバイアスがかかるが、州ごとの固定効果を利用したり、住宅価格指数を用いてシミュレーションした住宅価格を用いて分析したりすることで、そのようなバイアスがないことを確認している。

## サンプル
- アメリカ合衆国の女性を対象とし、1985年から2007年までの四半期パネルデータを使用した。
- 調査対象は25歳から44歳の女性。
- 対象期間の多くで住宅価格は上昇局面にあり、下落する局面にあった割合は16.8%であった。
- データは米国疫病予防管理センターのNational Vital Statistics Reports、連邦住宅金融局の住宅価格指数、ミシガン大学による収入動態に関するパネル調査から収集された。

## 結果
- 住宅価格が10万ドル増加すると、世帯で住宅を保有する女性の合計出生数が0.22上昇し、これは出生率が16～18%増加するのに相当する。
  - もともとの分析で除いていた15-19歳の女性に関しては、出生率が18%減少する。
- 影響の大きさは子供を1人持つ女性が一番大きく、次に子供を2、3人持つ女性について大きかった。一方で、子供を持たない女性に関しては影響が見られなかった。
- 住宅価格が変動しても、賃貸住宅に住む女性の出生率には影響がない。
- 女性の収入別では、収入が下位25%の女性については影響が見られなかった。
- 住宅価格が減少した場合の出生率の減少は有意ではなかった。ただし、この結果はサンプルサイズ不足が原因である可能性がある。

## 研究の弱点
- 女性の収入をコントロール変数として用いているが、その変化は外生化されていないため、収入の出生率に対する影響については分析できていない。

- 既にいる子供の人数や、世帯収入などの違いが、住宅価格の変動による出生率の変化にどう影響しているかについて、より詳細な分析が必要である。
- 価格上昇局面と下落局面では影響の度合いが異なっているため、本研究の対象期間の後に起きた住宅バブルの崩壊が出生率にどのように影響したかについてはさらなる研究が求められる。


## 書誌情報
- Lovenheim, M. F., & Mumford, K. J. (2013). Do family wealth shocks affect fertility choices? Evidence from the housing market. *Review of Economics and Statistics, 95*(2), 464-475. https://doi.org/10.1162/REST_a_00266
