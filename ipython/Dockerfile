FROM miniconda3

LABEL maintainer=@jurinco

RUN conda update conda && \
    conda install --quiet --yes ipython && \
    conda clean -tipsy

CMD ["ipython"]

