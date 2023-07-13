# gpt-python-examples

## 環境構築

```
poetry config virtualenvs.in-project true
```

```
poetry install
```

```
poetry add ipykernel -D
```

## 環境構築備忘録

1. VSCode に Jupyter Extention と Python Extention を入れる
2. VSCode で project-root にしたいディレクトリを開く
3. Terminal 展開
4. root で poetry init
5. .venv を project-root に作成するための設定変更 `poetry config virtualenvs.in-project true`
6. `poetry install`
7. project-root に .venv が生成される
8. `poetry add ipykernel -D`
9. 使用する library の追加 poetry add ${library}
10. 動作させる notebook(*.ipynb) を開く
11. コマンドパレットを開くcommand + shilft + p
12. Jupyter: Select Interpreter to Start Jupyter Server を選択
13. ('.venv': poetry) を選択
14. notebook(*.ipynb) を動かす

参考サイト：[VSCode x Poetry x Jupyter 備忘録](https://zenn.dev/rayuron/articles/d52e325265efa5)
