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
    conda install -y pybigwig

#RUN pip install sldp
RUN pip install git+https://github.com/zj-liu/sldp.git
