FROM microsoft/dotnet

RUN mkdir /myapp
WORKDIR /myapp

ADD project.json /myapp/project.json
RUN dotnet restore

ADD . /myapp
