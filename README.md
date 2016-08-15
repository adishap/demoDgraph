# demoDgraph
It contains the demo section for dgraph website

To execute the demo section:
1. sudo docker run -p 81:80 -v $SOURCE_DIR/demoDgraph/app:/data -v $SOURCE_DIR/demoDgraph/nginx:/etc/nginx -i -t nginx

$SOURCE_DIR -  path to source directory

2. Goto http://localhost:81 to run the demo.