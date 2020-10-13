FROM continuumio/continuumio/anaconda3:5.2.0

RUN conda config --add channels conda-forge && \
    conda config --add channels bioconda && \
    conda config --add channels omnia && \
    conda config --add channels imperial-college-research-computing 

RUN conda install -y scipy=1.2.1 && \
    conda install -y tensorflow-gpu=1.14.0 && \
    conda install -y keras=2.2.5 && \
    conda install -y opencv=3.4.2 && \
    conda install -y scikit-learn=0.22 

RUN conda install -y meme && \
    conda install -y crossmap && \
    conda install -y matplotlib
    conda install -y pybigwig