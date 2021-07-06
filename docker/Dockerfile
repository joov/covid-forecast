FROM jupyter/minimal-notebook


COPY requirements.txt .
RUN pip install -r requirements.txt

WORKDIR /usr/app

ENV JUPYTER_ENABLE_LAB=yes

# RUN jupyter labextension install jupyterlab_vim && \
#     jupyter labextension install @jupyterlab/dataregistry-extension && \
#     pip install --upgrade jupyterlab-git && \
#     jupyter lab build

