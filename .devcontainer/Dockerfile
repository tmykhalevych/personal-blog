FROM drecom/ubuntu-ruby

RUN apt-get update && \
    apt-get -y install git wget zsh gcc g++

RUN sh -c "$(wget -O- https://github.com/deluan/zsh-in-docker/releases/download/v1.1.2/zsh-in-docker.sh)" -- \
    -t robbyrussell \
    -p git

RUN gem install bundler jekyll
RUN gem update --system
