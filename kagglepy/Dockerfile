FROM jupyter/notebook
LABEL maintainer wuhao1542@yahoo.com

RUN pip2 install numpy scipy pandas matplotlib seaborn scikit-learn && \
    pip3 install numpy scipy pandas matplotlib seaborn scikit-learn

CMD ["jupyter-notebook", "--NotebookApp.token=", "--no-browser"]
