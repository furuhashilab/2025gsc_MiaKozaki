# 2025gsc_MiaKozaki
2025年ゼミ論
## テーマ
プロ野球試合前後における都市回遊性の分析

## 概要/Abstract

プロ野球観戦が都市に与える人流の影響に着目し、横浜スタジアムを事例として
ナイターとデーゲームの試合前後における周辺回遊パターンの差を明らかにすることを目的とする。
人流データと空間要因データ（飲食店の密度・営業時間、観光資源、広場・歩行空間など）を用いて、
試合日と非試合日、ナイターとデーゲームの人流差を比較し、空間要因との関連を分析する。
本研究により、時間帯や空間要因が回遊性（スタジアム到着前後に、500m以上離れた複数のPOIに滞在したかどうか）に与える影響を把握し、都市・商業施策への具体的提言に資する知見を提供することを目指す。

This study focuses on the impact of professional baseball games on urban mobility, taking Yokohama Stadium as a case study.  
The objective is to clarify the differences in surrounding mobility patterns before and after night games and day games.  
By using human flow data together with spatial factors (such as restaurant density and opening hours, tourist attractions, public squares, and pedestrian spaces), the study compares mobility patterns on game days and non-game days, and examines the relationship between spatial factors and human flow differences.
The expected contribution of this research is to provide insights into how time periods and spatial characteristics influence urban mobility, and to inform concrete urban and commercial policy recommendations.

## 研究目的
- ナイターとデーゲームでの試合前後の人流差を明らかにする  
- 都市空間要因（飲食店密度・営業時間、観光資源、広場・歩行空間など）との関係を検討
- 分析結果をもとに、横浜スタジアム周辺の都市・商業施策に活かせる知見を提示

## 研究方法
1. **データ収集**  
   - 人流データ：現在、複数のデータソースを検討中  
        -  候補：RAIDA（1kmメッシュ）、民間アプリGPSデータ（Agoop等）、キャリア系携帯位置情報（ドコモ等）  
        - 選定方針：空間解像度（250〜500m程度）、時間解像度（30分程度）、コスト・調達期間を考慮して決定予定  
        - 必要に応じて現地観察調査で補完する 
   - 試合日程：NPB公式、DeNAベイスターズ公式  
   - 空間要因データ：OpenStreetMap、Google Mapsなど 

2. **分析フレーム**  
   - 人流差分の可視化  
     - ゲーム日vs非ゲーム日  
     - ナイターvsデーゲーム  
     - 試合前（-2h〜開始）、試合後（終了〜+2h）の比較  
   - 空間要因との関連分析  
     - 飲食店密度・夜間営業比率  
     - 駅からの距離・歩行空間特性  
     - 公園・広場の有無  
