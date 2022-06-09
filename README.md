import chardet
import pathlib

	a = input("好きな文字をいれてください") //文字入力
	chardet.detect(a)			//文字コードの判別・変換
	'(a)'.encord('utf-8')
	'(a)'.encord('ascll')
	'(a)'.encord('Shift_JIS')
	
	lines = a.readlines()			//改行コードの判別・変換
	lines = a.splitlines()

	a.isdecimal()				//文字種別の判定（十進数字、数字、文字、英字）
	a.isdigit()
	a.isnumeric()
	a.sialpha()
