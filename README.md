### Non-system tables

- BookImageMst
- Settings
- MyScheduleMst
- SystemInfo
    OSのバージョン
- BookMst
    教科書のリスト
- ScheduleTbl  
    終了分含めたスケジュール  
    学習、教科書がIDで参照されてる  
- ProgressTbl  
    全教科書の全ページの進捗情報  
    スケジュールとの辻褄を合わせる必要があるかも？  
- RecordTbl  
    学習のリスト  
    Scheduleカラムが文字化けしてるので現時点で意味不明  
    数値として読むと離散値に見えるけどマスクではなさそう  
