FROM continuumio/continuumio/miniconda3:4.8.2

RUN conda config --add channels conda-forge && \
    conda config --add channels bioconda && \
    conda config --add channels omnia && \
    conda config --add channels imperial-college-research-computing 

RUN conda install -y python=3.6.5 && \
    conda install -y scipy=1.2.1 && \
    conda install -y tensorflow-gpu=1.14.0 && \
    conda install -y keras=2.2.5 && \
    conda install -y opencv=3.4.2 && \
    conda install -y scikit-learn=0.22 &&\
    conda install -y meme=5.0.5 && \
    conda install -y crossmap=0.4.1 && \
    conda install -y matplotlib=3.1.3 && \
    conda install -y pybigwig=0.3.13 && \
    conda install -y pybedtools=0.8.1

RUN conda install -y ucsc-bigbedtobed && \
    conda install -y ucsc-bedgraphtobigwig && \
    conda install -y ucsc-bedtobigbed && \
    conda install -y ucsc-bigwigtobedgraph && \
    conda install -y ucsc-liftover && \
    conda install -y ucsc-bedsort && \
    conda install -y ucsc-bedremoveoverlap

RUN pip install scikit-image==0.16.2
RUN pip install keras-vis