

# Pull base image.
FROM python:3.7
ENV PYTHONUNBUFFERED 1

# Setup linkages to code repositories and add to image

WORKDIR /var/www/propertyappraisal/Scraping


ADD WebScraping.py /
# RUN pip install urllib
RUN pip install requests
RUN pip install lxml
RUN pip install bs4
# RUN pip install urllib3
RUN pip install elasticsearch
RUN pip install psycopg2
RUN pip install psycopg2-binary
RUN pip install elasticsearch-dsl
# CMD [ "python", "WebScraping.py" ]