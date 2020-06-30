# tensorflow2_gpu_nlp
Dockerfile to build image using tensorflow 2 with gpu and jupyter lab support for natural language processing tasks.
Port 8888 is for jupyter lab and 6006 is for tensorboard

Libraries include:
- tensorflow-gpu
- tensorboard
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
`docker container run -it --gpus all -v /path/to/directory:/tf/notebooks/ --rm -p 8888:8888 -p 6006:6006 tensorflow2_gpu_nlp`

### Commands to start Tensorboard:
`%load_ext tensorboard`
`%tensorboard --logdir /path/to/logs/ --host 0.0.0.0`
