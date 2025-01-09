FROM squidfunk/mkdocs-material as BUILD
RUN pwd
WORKDIR /mkdocs
COPY . .
RUN pip3 install -r requirements.txt
RUN mkdocs build

FROM nginxinc/nginx-unprivileged
COPY --from=BUILD ./mkdocs/site ./usr/share/nginx/html
EXPOSE 8000