FROM python
RUN pip install notebook && \
    mkdir -p /opt/app-root/src/.jupyter
COPY jupyter_notebook_config.py /opt/app-root/src/.jupyter/jupyter_notebook_config.py
EXPOSE 8888
CMD jupyter notebook

