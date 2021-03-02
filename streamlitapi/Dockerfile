FROM python:3.7-slim
WORKDIR /deploy/streamlitapi
COPY ./requirements.txt /deploy/streamlitapi
RUN pip install -r requirements.txt
COPY ./webapp.py /deploy/streamlitapi
EXPOSE 8501
CMD ["streamlit", "run", "webapp.py"]