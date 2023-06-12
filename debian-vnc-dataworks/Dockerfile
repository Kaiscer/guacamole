FROM alexaib/debian-vnc:latest

RUN apt install -y snapd wget

RUN wget https://github.com/alexaib2002/project-dataworks_base/releases/download/v1.0.0/data-works_1.0.0_amd64.snap && snap install ./data-works_1.0.0_amd64.snap --dangerous