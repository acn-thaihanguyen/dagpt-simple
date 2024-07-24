# DAGPT (スマートデータ分析およびインタラクティブビジュアライゼーションツール)

このリポジトリには、ユーザーがデータを分析し、インタラクティブなビジュアライゼーションを作成するのに役立つStreamlitベースのWebアプリケーションが含まれています。これらのアプリケーションを使用すると、ユーザーはCSVファイルをアップロードし、自然言語でデータを問い合わせ、Tableauの機能に似たインタラクティブなプロットを生成できます。

## アプリケーション概要

1. **データとのチャット** (`1_📊_Chat_With_Your_Data.py`)
2. **インタラクティブビジュアライゼーションツール** (`2_📈_Interactive_Visualization_Tool.py`)

### データとのチャット

アップロードしたCSVデータを自然言語で問い合わせ、結果をインタラクティブに視覚化できます。

### インタラクティブビジュアライゼーションツール

ユーザーがビジュアライゼーションを通じてデータをインタラクティブに探索できるインターフェースを提供します。

### 機能

- **CSVファイルのアップロード**: ユーザーはサイドバーを通じてCSVファイルをアップロードできます。
- **自然言語による問い合わせ**: ユーザーは自然言語で問い合わせを入力でき、AIモデルが応答とビジュアライゼーションを生成します。
- **インタラクティブなビジュアライゼーション**: アプリはPythonのプロットコードを実行し、生成されたプロットを表示できます。
- **チャット履歴**: ユーザーの問い合わせとAIの応答の履歴を表示します。
- **インタラクティブデータ探索**: ユーザーはTableauに似たグラフィカルインターフェースを使用してプロットを作成およびカスタマイズできます。

### 実行方法

1. リポジトリをクローンします:

   ```sh
   git clone https://github.com/acn-thaihanguyen/dagpt-simple.git
   cd dagpt-simple
   ```

2. 仮想環境を作成し、必要な依存関係をインストールします:

   ```sh
   python -m venv .venv
   source .venv/bin/activate
   pip install -r requirements.txt
   ```

3. Streamlitアプリケーションを実行します:

   ```sh
   streamlit run 1_📊_Chat_With_Your_Data.py
   ```

## ライセンス

このプロジェクトはMITライセンスの下でライセンスされています。詳細は[LICENSE](LICENSE)ファイルを参照してください。

## 謝辞

- [Streamlit](https://streamlit.io/)
- [LangChain](https://github.com/langchain-ai/langchain)
- [PyGWalker](https://github.com/Kanaries/pygwalker)
- [OpenAI](https://openai.com/)
