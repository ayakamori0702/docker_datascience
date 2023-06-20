FROM jupyter/datascience-notebook:bada6c21e945

RUN pip install --upgrade pip 

COPY ./requirements.txt /tmp/requirements.txt 
RUN pip install --no-cache-dir -r /tmp/requirements.txt

ENTRYPOINT ["jupyter-lab", "--ip=0.0.0.0", "--no-browser" , "--allow-root", "--NotebookApp.token=''"]
