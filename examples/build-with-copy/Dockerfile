#docker image build -t ex-build-copy .
#docker container run -p 8080:81 ex-build-copy
FROM nginx

LABEL maintainer 'Fernando Souza <fernando.de.souza@gmail.com>'

RUN echo '<h1>Sem comentario</h1>' > /usr/share/nginx/html/conteudo.html

COPY *.html /usr/share/nginx/html/