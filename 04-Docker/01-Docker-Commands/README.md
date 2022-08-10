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
