FROM python:3.7-slim
ENV PYTHONUNBUFFERED=TRUE
RUN mkdir src
WORKDIR /src

RUN pip install notebook
RUN pip install jupyterlab
CMD ["jupyter", "notebook", "--port=8888", "--no-browser" , "--ip=0.0.0.0", "--allow-root"]



