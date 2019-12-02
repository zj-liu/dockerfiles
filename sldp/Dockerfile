FROM continuumio/miniconda2:latest

RUN conda config --add channels r && \
    conda config --add channels bioconda

RUN conda install -y scipy && \
    conda install -y numpy && \
    conda install -y pandas && \
    conda install -y matplotlib

RUN conda install -y pysam && \
    conda install -y pybedtools && \
    conda install -y pysnptools 

RUN pip install sldp

RUN apt-get install -y mesa-utils
