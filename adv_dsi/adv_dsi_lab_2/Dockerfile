FROM jupyter/scipy-notebook:0ce64578df46

RUN conda install fbprophet

ENV PYTHONPATH C:\Users\Me\Anaconda3\envs\rstudio\lib\site-packages\twisted\python:/home/jovyan/work

RUN echo export PYTHONPATH=/home/jovyan/work >> ~/.bashrc

WORKDIR /home/jovyan/work
