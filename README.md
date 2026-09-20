# flight-feed-data

日航宗（JAL）・全日宗（ANA）アプリが取り込む共通時刻表フィードの配信先（GitHub Pages）。

- 配信URL: `https://pplog4.github.io/flight-feed-data/shared-flights.json`
- 生成元: [pplog4/shugyoji-app](https://github.com/pplog4/shugyoji-app) の `server/flight-data/`（管理者が実行。手で編集しない）
- 出典: 公共交通オープンデータセンター（ODPT）の JAL・ANA フライトスケジュール。
  [公共交通オープンデータ基本ライセンス](https://developer.odpt.org/terms/data_basic_license.html)。
  本フィードは同センターの提供データを元に個人開発者が加工したもので、JAL・ANA・ODPTの公式配信ではありません。
  実際の運航状況・最新の時刻は各社公式でご確認ください。
- 冬季補助時刻表: FlyTeam掲載のJAL・ANA便別時刻表（2026-09-20取得）。アプリ収録・再配信の提供元承諾取得済みと管理者が確認。各行の適用期間・曜日を保持し、期間不明のコードシェア対応は時刻表へ展開しません。
- 現在の冬季補助データはJAL 134便名・411期間行、ANA 146便名・379期間行。全提携会社・全コードシェアを網羅したものではありません。運航便名の未確認はnull、未掲載日の時刻は補間しません。
- 問い合わせ先: 各アプリのサポートページ（App Store / Google Play の掲載情報）を参照。

認証値・個人情報は含めません。
