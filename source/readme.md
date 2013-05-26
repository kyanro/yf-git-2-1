### source フォルダ以下のみが抽出されているリポジトリ

1st commit からは
	source/source.txt
のみ

2nd, 3rd commitはsource フォルダ以外の変更なので履歴として残らない

4th commit は
	source/source2.txt
がそのまま抽出される

5th commit からは、サブフォルダの中(folder1)の
	source/folder/source2.txt
がそのまま抽出されることを確認