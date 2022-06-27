# Sqdarkとは?
SqdarkはSqliteを簡単に操作出来るようにするライブラリです。<br>
sqdark.pyを外部からimportして利用することが出来ます。

# Docs
## sqdark.add_table(str db_file, str table_name) -> boolean
テーブルを追加します。
## sqdark.add_value(str db_file, str table_name, str col, str value) -> boolean
値を追加します。
## sqdark.get_tables(str db_file) -> list
テーブルをリスト形式で取得します。
## sqdark.get_values(str db_file, str table_name) -> dict
テーブル内の値をDict形式で取得します。
