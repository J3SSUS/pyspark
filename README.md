# Commands

Create Docker Image base on Dockerfile

    docker build -t pyspark_lab .

Create a Docker Container with the created image

    docker run -v "%cd%":/home/jovyan/SparkProjects/Project1/ --name spark_submit_run_pyspark_example pyspark_lab:latest

    docker run --rm -v "%cd%":/home/jovyan/SparkProjects/Project1/ --name spark_submit_run_pyspark_example pyspark_lab:latest