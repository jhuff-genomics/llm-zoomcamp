# Monitoring Homework

Start Jupyter for the dev notebook:
```
$ uvx --python 3.12 jupyter lab
```

For qdrant server:
```
$ docker pull qdrant/qdrant

$ docker run -p 6333:6333 -p 6334:6334 \
   -v "$(pwd)/qdrant_storage:/qdrant/storage:z" \
   qdrant/qdrant
```
