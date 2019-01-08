# spark-kubernetes-docker-image
Docker image use to run Apache Spark inside Kubernetes cluster as indicated here: https://spark.apache.org/docs/latest/running-on-kubernetes.html#docker-images

Get the image from here: https://cloud.docker.com/repository/docker/thangbui/spark . 
Tags:  
  <version>-f tag: Dockerfile to build for JVM based Jobs. By default builds the Dockerfile shipped with Spark.  
  <version>-py tag: Dockerfile to build for PySpark Jobs. Builds Python dependencies and ships with Spark.  
  <version>-r tag: Dockerfile to build for SparkR Jobs. Builds R dependencies and ships with Spark.  
