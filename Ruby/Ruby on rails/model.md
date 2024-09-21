# model関係

## ActiveRecordメソッド　　
モデルのテーブル操作の時にデータを保存する時やデータを取得する時に使われるメソッドである。  
### allメソッド   
テーブルデータを全て取得する。ex Memoテーブルから取得する時　Memo.all
### findメソッド　　
引数としてレコードのidを指定してそのidに対応するレコードデータを取得する。 ex Memoテーブルのidが1なら　Memo.find(1)
### newメソッド　　
クラスのインスタンスを生成する。 ex Memo.new
### saveメソッド　　
クラスのインスタンスを保存する。 ex Memo.save 
