# data-mining
## Docker Image
    docker pull jupyter/all-spark-notebook

    docker run -it --rm -p 8888:8888 -v <work_directory>:/home jovyan/work -w /home/jovyan/work jupyter/all-spark-notebook

## Docker-compose
    curl -LO https://raw.githubusercontent.com/bitnami/bitnami-docker-spark/master/docker-compose.yml
    
    docker-compose up

  
