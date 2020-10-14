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
    conda install -y scikit-learn=0.22 

RUN conda install -y meme=5.0.5 && \
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

RUN pip install attrs==19.3.0
RUN pip install keras-vis==0.5.0
RUN pip install scikit-image==0.16.2

# to test
#imageio=2.8.0=pypi_0
#importlib-metadata=1.5.0=pypi_0
#more-itertools=8.2.0=pypi_0
#multipledispatch=0.6.0=pypi_0
#packaging=20.1=pypi_0
#pillow=7.0.0=pypi_0
#pluggy=0.13.1=pypi_0
#py=1.8.1=pypi_0
#pytest=5.3.5=pypi_0
#pywavelets=1.1.1=pypi_0
#zipp=3.0.0=pypi_0
