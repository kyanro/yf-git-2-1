# 今回利用したコマンドのhistory

	git init
	mkdir hoge && mkdir fuga && mkdir source
	touch hoge/hoge.txt && touch fuga/fuga.txt && touch source/source.txt
	git add . && git commit -am "1st commit"

	touch hoge/hoge2.txt     && git add . && git commit -m "2nd commit. add hoge2"
	touch fuga/fuga2.txt     && git add . && git commit -m "3rd commit. add fuga2"
	touch source/source2.txt && git add . && git commit -m "4th commit. add source2"

	mkdir source/folder1/
	touch source/folder1/source3.txt
	git add .
	git commit -m "5th commit. add source/folder1/source3"

	git subtree push /c/repos/source/ master --prefix source/

