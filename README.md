

```shell
python3 -m venv .venv

# Linux または macOS の場合
source .venv/bin/activate 

# Windows の場合
.venv\Scripts\activate   

```

my_project/
├── .venv/             # 仮想環境のディレクトリ
├── src/               # ソースコードを格納するディレクトリ  │   ├── __init__.py
  │   └── main.py
├── tests/             # テストコードを格納するディレクトリ
 │   └── test_main.py
└── requirements.txt   # 必要なパッケージをリストアップしたファイル

