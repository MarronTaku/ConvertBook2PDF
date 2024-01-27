# ConvertBook2PDF
ブラウザ上でアクセスした電子書籍（主にKindleなど）を自動でスクリーンショットし、PDFを生成します。
電子書籍を指定したページ分を自動でスクリーンショットを行います。

## インストール方法
venvでPython環境を構築します。
```bash
# venv39の命名は任意
python3.9 venv -m venv39
```

## 使い方
1. pythonの実行
```bash
python3 main.py
```
2. スクリーンショット範囲をクリックで指定  
クリック1回目はスクリーンショットを行うブラウザ選択する。
次に、スクリーンショットを行う左上座標、右下座標の順にクリックする
3. 画面が自動で切り替わることを確認
4. 全てのスクリーンショットが完了したら「output_」フォルダにpngとpdfファイルが出力