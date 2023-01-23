FROM jupyter/scipy-notebook

RUN python -m ipykernel install --user

COPY ./requirements.txt /tmp/requirements.txt
RUN pip install -r /tmp/requirements.txt

