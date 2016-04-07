

docker-compose scale spark-slave=3


spark-shell --master spark://$(docker-machine ip $(docker-machine active)):7077
