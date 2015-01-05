caffe_docker
============

An CPU only docker file to run caffe web demo easier

Original version taken from: tleyden5iwx / caffe in docker hub


1) sudo docker run -p 5000:5000  -i -t jmozah/caffe-web-demo /bin/bash

2) in the prompt.. 
      -> cd /opt/caffe
      -> python examples/web_demo/app.py

3) in the browser.. goto.. http://localhost:5000 to access the web demo

