# lecture-ai-engineering
AIエンジニアリング実践講座（公開用リポジトリ）

# 演習課題：モデル改善

## やったこと

- LLMモデルを `google/gemma-2-2b-jpn-it` から `rinna/japanese-gpt-neox-3.6b` に変更
- `config.py` の `MODEL_NAME` を変更し、推論処理は `llm.py` で保持

## 実行方法

- `02_streamlit_app/app.py` を `streamlit run` で実行
