### Non-system tables
SystemInfo
BookMst
BookImageMst
RecordTbl
ScheduleTbl
Settings
MyScheduleMst
ProgressTbl

- RecordTbl
    学習のリスト
    Scheduleカラムが文字化けしてる
        現時点で不明
        数値として読むと離散値に見えるけどマスクではなさそう
- BookMst
    教科書のリスト
- ScheduleTbl
    終了分含めたスケジュール
    学習、教科書がIDで参照されてる
- ProgressTbl
    全教科書の全ページの進捗情報
    スケジュールとの辻褄を合わせる必要があるかも？
