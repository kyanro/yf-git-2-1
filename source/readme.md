### source フォルダ以下のみが抽出されているリポジトリ

1st commit からは

	source/source.txt

のみが抽出される。`他の二つのファイル(hoge.txt, fuga.txt)は含まれない`

2nd, 3rd commitはsource フォルダ以外の変更なので`履歴として抽出されない`

4th commit は

	source/source2.txt

がそのまま抽出される

5th commit からは、`サブフォルダの中(folder1)`の

	source/folder/source2.txt

がそのまま抽出される。