FROM nbgallery/jupyter-alpine

RUN pip3 install --upgrade pip
RUN pip3 install --upgrade jupyter
RUN pip3 install --upgrade notebook

RUN pip3 install --upgrade calysto-scheme
RUN python3 -m calysto_scheme install

RUN mkdir /app /.local && chmod 777 /app /.local

WORKDIR /app
CMD jupyter notebook --ip=0.0.0.0 --port=8080

