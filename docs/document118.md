---
id: 118 
title: "育児休業給付の所得代替率の増加" # 引用符付きで研究対象の政策や変数を端的に示す名称を記入してください。
description: "育児休業給付の所得代替率の増加による女性の前職復職率への影響" # 引用符付きで一文以内で政策の簡単な概要を記入してください。
date: "2022-11-10" # 引用符付きで記入日を入れてください。
category: "fertility" # レビューのカテゴリーを記入してください。カテゴリーがない場合は新規で作成してください。その際、カテゴリを端的に示す英単語を選んでください。
categoryLabel: "少子化対策" # レビューのカテゴリーラベルを記入してください。新規の場合はカテゴリを端的に示す名称を選んでください。
tables: [
  {
    "title": "女性の育休後前職復職率", # 評価指標の名称を簡潔に記入してください。
    "effectiveness": "効果なし", # 期待される効果があったことが確認された場合は"効果あり"、期待される効果がなかったり、逆効果だったことが確認された場合は"効果なし"、状況によって効果があったりなかったりする場合は"ミックス"、検出力不足や研究の不備によって結論が出せない場合は"不明" としてください。
    "strength": 2 # 証拠の強さは https://cyberagentailab.github.io/EBPMDB/sms を参照してください。
  }
]

points:
    - 育児休業給付の所得代替率の増加は、女性の前職復職率に影響を与えなかった。
    - 第１子、第２子、学歴に関わらず影響なし
    - およそ70%の女性が出産後に労働市場から完全に撤退する


contacts:
  - 土生 一心

---

## 背景 
- 育児休業給付の所得代替率の増加によって、育休後に労働市場から完全に離れることが多い女性の労働供給が増加するのかについて、定量的に検証した。
- 日本の制度では、基本給付金と職場復帰給付金に分かれ、給付金を全て受け取るには復職の必要がある（現在は基本給付金と職場復帰給付金は統合）。

## 介入
- 育児休業給付の所得代替率の増加
- 1995年改正 0%から25%
- 2001年改正 25%から40%


## 評価指標
- ３年以上の正規雇用後、出産を経験した女性の前職復職率
- 出産年月日・雇用状態のデータを利用して、産前2年間と産後2年間の前職における雇用状態を作成して計算。

## 分析方法
- 回帰分析による介入群と対照群の比較

## 証拠の強さ
- SMS:2
- 根拠 
    - 介入群と対照群の横断的比較を行っている
    - 出産時期によって、介入を受ける女性(介入群)と受けない女性(対照群)が正確に分けられている
    - 介入群と対照群について、学歴・勤続年数・会社の規模・産業構成などが平均的に似通っていることを確認できている
    - 政策の公表によって、恩恵を受けるために出産行動を変化させるといった操作がないことを確認
    - 男性や子どもを持たない女性との差分の差法による分析により、給付金以外のマクロ経済的変化が影響を与えていないことを確認


## サンプル
- 日本統計局による『就業構造基本調査報告』, 1997-2002年, 15才以上の世帯員が対象。
- 2001年の改革：2000年10月~2001年9月までに出産した女性(介入群)が1298人、1999年10月~2000年9月までに出産した女性(対照群)が1393人
- 1995年の改革：1995年10月~1996年9月までに出産した女性(介入群)が1634人、1993年10月~1994年9月までに出産した女性(対照群)が1809人
- 性別が同一のもの３人以上のみで構成される世帯、8人以上の世帯のメンバーは除く

## 結果
- 2001年の改革でも、1995年の改革でも、第1子出産に限った場合の介入群と対照群の間に有意な差は見られず、ほぼ0に近い値。
- 第2子出産の場合でも、学歴別に検証した場合でも同様に0に近い差。
- 育児休業が終わった後、つまり１歳児以降の育児に関しては政策的支援が薄いことや、保育所問題など育児システムの不備、伝統的家族制度といったことが、育児休業の際の給付金を増やしても女性の労働供給は変わらない原因として推測される。

## 研究の弱点
- 

## 書誌情報
- Asai, Y. (2015a). Parental leave reforms and the employment of new mothers: Quasi-experimental evidence from Japan. Labour Economics, 36, 72–83. https://doi.org/10.1016/j.labeco.2015.02.007
