# setting_ipynb_for_Paperspace
このリポジトリはPaperspaceで、私がカスタムしたDocerイメージを使用したものを前提としています。

## Docker イメージ

以下の Docker イメージを使用してください：

```bash
shibashiba2/paperspace-gradient-base-pytorch241:v6
```

Dockerイメージを使用する方法については、以下のURLを参考にしてください。

https://editor.note.com/notes/nb2913ed01a79/edit/

Paperspaceのセルコマンドの実行もしくはターミナルでコマンドを実行するか、手動でノートブックディレクトリに、このリポジトリに公開されているipynbファイルをダウンロード・アップロードするのが目的です。

## 使用方法

以下のコマンドを Jupyter Notebook のセルにコピーして実行してください：

```python
%cd /notebooks
!wget -r -np -nd -A "*.ipynb" -P ipynb_files https://raw.githubusercontent.com/Shiba-2-shiba/setting_ipynb_for_Paperspace/main/

```
ノートブックディレクトリに配置されたら、そのセルコマンドを個々でカスタムして使いやすくしてください。
