# jupyterlab with livy client and Spark standalone cluster  


## Starting the Docker container

* Step 1: Clone the repository by running the following command
    ```
    git clone  //todo
    ```

* Step 2: Build and start the container by running the following command inside the cloned repository:
    ```
    docker-compose build
    ```

* Step 3:
    * Visit `locahost:8080` in your browser and make sur spark cluster is running  
    * Visit `localhost:8998` in your browser and make sure the Livy Server is running
    * Visit `localhost:8888/?token=easy` in your browser and make sure jupyter lab is running
## About

* The Java SE 1.8 JDK
* The Hadoop (2.7) and Apache Spark (2.4.6) binaries
* Apache Livy (0.7.0) source files
* Juputer base nootbook and jupyterlab ebabled - latest (for now)

## Preequesites

In order to be able to run you will have to first install **Docker** (Community Edition is sufficient):

* [Installing Docker](https://docs.docker.com/get-docker/)

## Documentation
* [SparkMagic](https://github.com/jupyter-incubator/sparkmagic)
* [Livy](https://livy.incubator.apache.org/)
* [Spark standalone - bitnami image](https://github.com/bitnami/bitnami-docker-spark#how-to-use-this-image)

## Notes

* This version still does not support batch request to livy - stay tuned (or contribute :))
