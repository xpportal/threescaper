# threescaper

A website for loading Townscaper models into three.js

# TODO:
## Exporter
- Currently exports `.obj` to `.glb` after dragging `.obj` into the box
  - Texture is still missing

# Repo Setup Steps
- Clone repo
- `npm install`
- `docker run --name threescaper -v $PWD:/usr/share/nginx/html:ro -p 8080:80 nginx:latest`

Go to `localhost:8080`
