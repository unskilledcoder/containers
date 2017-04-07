FROM jupyter/notebook
LABEL maintainer wuhao1542@yahoo.com

RUN pip3 install --no-cache-dir numpy scipy pandas matplotlib seaborn scikit-learn
RUN pip3 install --no-cache-dir tensorflow

CMD ["jupyter-notebook", "--NotebookApp.token=", "--no-browser"]
