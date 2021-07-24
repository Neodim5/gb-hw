FROM python:3.9-slim
MAINTAINER Dmiytry Neklyudov <neodim5@mail.ru>
#
# install dependencies
#RUN pip install --upgrade pip
#COPY ./requirements.txt .
#RUN pip install -r requirements.txt

COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt
#
#RUN adduser user1
RUN useradd -u 9999 user1
USER user1
#
#
COPY app.py .
# RUN adduser -D user1
#ENTRYPOINT [ "/app" ]
#
CMD [ "python", "app.py" ]
#
EXPOSE 8080