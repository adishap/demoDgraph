# demoDgraph
It contains the demo section for dgraph website

1. To execute the demo section:<br>
<code>sudo docker run -p 81:80 -v $SOURCE_DIR/demoDgraph/app:/data -v $SOURCE_DIR/demoDgraph/nginx:/etc/nginx -i -t nginx</code>

$SOURCE_DIR -  path to source directory

2. Goto <a href="http://localhost:81">http://localhost:81</a> to run the demo.
