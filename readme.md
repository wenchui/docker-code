docker-make-base-images/mkimage-yum.sh

make centos base image for docker,run the command like this:

"nohup ./mkimage-yum.sh -y /etc/yum.conf centos7 &"

check the log which "tail -f nohup.out"

then run the command "docker images" check the centos images exist or not

centos7                                         7.9.2009                         86384d97cb44   47 minutes ago   419MB
