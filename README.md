# TOKYO2020オリンピック～水泳～

**機能**
* 競技種目別の結果<br>
    競技種目を選択して決定ボタンを押すと，選択した競技種目の結果を表示．
* メダルの個数<br>
    メダルの総数順に各チームの獲得したメダルの個数を表示．
* 得点<br>
    得点順に各チームがそれぞれの競技で獲得した得点を表示．
* 選手別の結果<br>
    選手を選択して決定ボタンを押すと，選択した選手の結果を表示．
* チーム別の結果<br>
    チームを選択して決定ボタンを押すと，選択したチームの全選手の結果を表示．

**実装**
* フロントエンド言語：
  <img src="https://img.shields.io/badge/-HTML5-E34F26.svg?logo=html5&style=plastic">
  <img src="https://img.shields.io/badge/-CSS3-1572B6.svg?logo=css3&style=plastic">
  <img src="https://img.shields.io/badge/-JavaScript-F7DF1E.svg?logo=javascript&style=plastic">
* バックエンド言語：
  <img src="https://img.shields.io/badge/-Python-3776AB.svg?logo=python&style=plastic">
* バックエンドフレームワーク：
  <img src="https://img.shields.io/badge/-Django-092E20.svg?logo=django&style=plastic">
* データベース：
  <img src="https://img.shields.io/badge/-SQLite-003B57.svg?logo=SQLite&style=plastic">
* 統合開発環境：
  <img src="https://img.shields.io/badge/-VSCode-007ACC.svg?logo=visualstudiocode&style=plastic">

**各ファイルの説明**
* manage.py：メインファイル
* conversion.py：tokyo2020.csvファイルの内容をdb.sqlite3ファイルにインポート
* requirements.txt：パッケージ一覧
* db.sqlite3：records_swimmingresult(id, sport, event, rank, athletes, team, record)
* tokyo2020.csv：1~8位のデータセット
* index.html：21世紀のオリンピックの開催年、都市、国の表示
* base.html：メタ情報やナビゲーションメニュー
* select_event.html：競技・種目の選択フォーム
* result.html：選択された種目の結果を表示
* medal.html：チーム別のメダルの個数
* score.html：チーム別の各競技で獲得した得点
* select_athlete.html：選手の選択フォーム
* athlete.html：選択された選手の結果を表示
* select_team.html：チームの選択フォーム
* team.html：選択されたチームの全結果を表示

*得点配分*
|順位|得点|
|:---:|:---:|
|1|8|
|2|7|
|3|6|
|4|5|
|5|4|
|6|3|
|7|2|
|8|1|
<br>

<br>

# TOKYO 2020 Olympic Games - Aquatics
#### Description:

**Function**
* Results of event<br>
    When you select a competition event and click the decision button, the results of the selected event will be displayed.
* Number of medals<br>
    Displays the number of medals won by each team in order of total number of medals.
* Score<br>
    Displays the points scored by each team in each event in order of score.
* Results by player<br>
    Select a player and click the decision button to display the results for the selected player.
* Results by team<br>
    Select a team and click the decision button to see the results of all players of the selected team.

**Implementation**
* Frontend Languages:
  <img src="https://img.shields.io/badge/-HTML5-E34F26.svg?logo=html5&style=plastic">
  <img src="https://img.shields.io/badge/-CSS3-1572B6.svg?logo=css3&style=plastic">
  <img src="https://img.shields.io/badge/-JavaScript-F7DF1E.svg?logo=javascript&style=plastic">
* Backend Languages:
  <img src="https://img.shields.io/badge/-Python-3776AB.svg?logo=python&style=plastic">
* Backend Frameworks:
  <img src="https://img.shields.io/badge/-Django-092E20.svg?logo=django&style=plastic">
* Database:
  <img src="https://img.shields.io/badge/-SQLite-003B57.svg?logo=SQLite&style=plastic">
* IDE:
  <img src="https://img.shields.io/badge/-VSCode-007ACC.svg?logo=visualstudiocode&style=plastic">

**Description of each file**.
* manage.py: Main file
* conversion.py: Insert contents of tokyo2020.csv file into db.sqlite3 file
* requirements.txt: Package List
* db.sqlite3: records_swimmingresult(id, sport, event, rank, athletes, team, record)
* tokyo2020.csv: Dataset of 1~8 ranks
* index.html: Display year, city, and country of the 21st century Olympics
* base.html: Meta information and navigation menu
* select_event.html: Selection form for events and disciplines
* result.html: Display of results for the selected event
* medal.html: Number of medals by team
* score.html: Scores won in each event by team
* select_athlete.html: Athlete selection form
* athlete.html: Display results of selected athlete
* select_team.html: Team selection form
* team.html: Display all results for the selected team

*Score distribution*
|rank|score|
|:---:|:---:|
|1|8|
|2|7|
|3|6|
|4|5|
|5|4|
|6|3|
|7|2|
|8|1|
<br>
