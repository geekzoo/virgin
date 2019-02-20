<pre># virgin
Base Core deb-bootstrap to build docker image ubuntu
comment out or change to your proxy export http_proxy=http://proxy:3128/

$sudo ./build-img-v2.sh -t temp/ubuntu debootstrap --include=ubuntu-minimal --components=main,universe bionic <br>
