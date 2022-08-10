```
1949  cd 04-Docker/
 1950  ls
 1951  cd 00-Setup/
 1952  ls
 1953  cat install-docker.sh
 1954  ls
 1955  ./install-docker.sh
 1956  docker version
 1957  docker images
 1958  docker ps -qa
 1959  docker rm $(docker ps -qa)
 1960  docker images
 1961  docker images -q
 1962  docker rmi $(docker images -q)
 1963  docker rmi $(docker images -q)  --force
 1964  docker images
 1965  docker ps
 1966  docker ps -a
 1967  docker run busybox echo "Welcome to the world of Docker"
 1968  docker container ls
 1969  docker container ls -a
 1970  docker run busybox echo "Welcome to the world of Docker"
 1971  docker container ls -a
 1972  docker run busybox echo "Test - 1"
 1973  docker run busybox echo "Test - 2"
 1974  docker container ls -a
 1976  docker run busybox lsop
 1977  docker container ls -a
 1978  docker container ls
 1979  docker container ls -a
```


```
1993  docker images
 1994  docker pull ubuntu
 1995  docker images
 1996  docker pull ubuntu:16.04
 1997  docker ps
 1998  docker images
 1999  docker pull amitvashist7/k8s-tiny-web
 2000  docker images
```
```
 1032  docker run -it ubuntu:16.04
 1033  docker ps
 1034  docker container ls
 1035  docker container ls -a
 1036  docker run -it ubuntu
 1037  history
 1038  docker run -it --name test-1 ubuntu
 1039  docker ps
 1040  docker ps -a
 1041  docker run -it --name test-1 ubuntu
 1042  docker run -d --name test-2 ubuntu
 1043  docker ps -a
 1044  docker run -itd --name test-3 ubuntu
 1045  docker ps -a
 1046  docker ps
 1047  docker stop test-3
 1048  docker ps
 1049  docker ps -a
 1050  docker start test-3
 1051  docker ps
 1052  docker attach test-3
 1053  docker ps
 1054  docker ps -a
 1055  docker start test-3
 1056  docker ps -a
 1057  docker attach test-3
 1058  docker ps
 1059  docker attach test-3
 1060  ls
 1061  docker ps
 1062  ls
 1063  docker ps -a
 1064  docker run -itd --name test-4 ubuntu
 1065  docker run -itd --name test-5 ubuntu
 1066  docker run -itd --name test-6 ubuntu
 1067  docker ps
 1068  docker inspect test-3
 1069  docker ps
 1070  docker ps -a
 1071  docker ps
 1072  docker ps -q
 1073  docker inspect $(docker ps -q)
 1074  docker inspect --format '{{.Name}} {{.State.Running}} {{.NetworkSettings.IPAddress}}' $(docker ps -q)
 1075  docker ps
 1076  docker ps -a
 1077  docker ps -aq
 1078  docker inspect --format '{{.Name}} {{.State.Running}} {{.NetworkSettings.IPAddress}}' $(docker ps -qa)
 1079  docker start test-2
 1080  docker inspect --format '{{.Name}} {{.State.Running}} {{.NetworkSettings.IPAddress}}' $(docker ps -qa)
 1081  docker ps
 1082  docker kill $(docker ps -q)
 1083  docker inspect --format '{{.Name}} {{.State.Running}} {{.NetworkSettings.IPAddress}}' $(docker ps -qa)
 1084  docker rm $(docker ps -aq)
 1085  docker ps -a
 1086  docker images
 1087  docker rmi busybox
 1088  docker images

```




```
cker-Images
 1107  ls
 1108  cd 02-Docker-Images/
 1109  ls
 1110  mkdir apache/v1
 1111  mkdir apache/v1 -p
 1112  ls
 1113  cd apache/
 1114  ls
 1115  cd v1/
 1116  ls
 1117  vim Dockerfile
 1118  ls
 1119  docker ps -a
 1120  docker run -itd ubuntu:16.04
 1121  docker ps
 1122  ls
 1123  docker build -t myapache .
 1124  docker images
 1125  docker run -d --name test-apache-1 myapache
 1126  docker ps
 1127  docker inspect 0~test-apache-11~
 1128  docker inspect test-apache-1
 1129  docker ps
 1130  curl 172.17.0.3
 1131  history
 1132  ls
 1133  docker ps
 1134  docker run -d --name test-apache-2 myapache
 1135  docker run -d --name test-apache-3 myapache
 1136  docker ps
 1137  docker inspect --format '{{.Name}} {{.State.Running}} {{.NetworkSettings.IPAddress}}' $(docker ps -qa)
 1138  curl 172.17.0.3
 1139  curl 172.17.0.4
 1140  curl 172.17.0.5
 1141  curl 172.17.0.6
 1142  curl 172.17.0.2
```

