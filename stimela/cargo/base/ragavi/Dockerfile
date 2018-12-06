FROM stimela/meqtrees:1.0.0
RUN docker-apt-install curl
RUN curl -sL https://deb.nodesource.com/setup_8.x | bash -
RUN docker-apt-install -y nodejs
ADD ragavi /ragavi
RUN pip install /ragavi
