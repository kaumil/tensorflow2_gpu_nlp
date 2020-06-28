# tensorflow2_gpu_nlp
Dockerfile to build image using tensorflow 2 with gpu and jupyter lab support for natural language processing tasks.

Libraries include:
- tensorflow-gpu
- scikit-learn
- pandas
- numpy
- bokeh
- chartify
- nltk
- textblob
- stanford-corenlp
- gensim
- spacy (with cuda support)
- polyglot
- jupyter-lab

### Command to run:
`docker container run -it --gpus all -v /path/to/directory:/tf/notebooks/ --rm -p 8888:8888 tensorflow2_gpu_nlp`
