FROM python:3.7

ENV PACKAGES \
        locales \
        curl \
        python-dev \
        git \
		vim \
		libfreetype6-dev \
		libatlas-base-dev \
		liblapack-dev \
		gfortran
		
RUN apt-get update && apt-get install -y $PACKAGES

ENV PIP_PACKAGES \
    numpy \
    scipy \
    matplotlib \
    scikit-learn \
	ggplot 
	
RUN pip install $PIP_PACKAGES

RUN apt-get clean