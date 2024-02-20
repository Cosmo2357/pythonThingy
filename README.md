

```shell
python3 -m venv .venv

# Linux または macOS の場合
source .venv/bin/activate 

# Windows の場合
.venv\Scripts\activate   

# パッケージのインストール
pip install -r requirements.txt



pip install --upgrade --quiet  elasticsearch langchain-openai tiktoken langchain

    docker run -p 9200:9200 -e "discovery.type=single-node" -e "xpack.security.enabled=false" -e "xpack.security.http.ssl.enabled=false" docker.elastic.co/elasticsearch/elasticsearch:8.9.0

docker-compose up -d

cd src
uvicorn main:app --reload
```



