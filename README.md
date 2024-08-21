# Spark_Installation

 - instalar e configurar o Hadoop Spark
 * sudo apt-get update
 * sudo apt-get install openjdk-11-jdk
 
 * wget https://dlcdn.apache.org/spark/spark-3.5.2/spark-3.5.2-bin-hadoop3.tgz
 * tar -xvzf spark-3.5.2-bin-hadoop3.tgz
 * sudo mv spark-3.4.0-bin-hadoop3 /usr/local/spark

 - Agora configure as variaveis de ambiente 
 * export SPARK_HOME=/usr/local/spark
 * export PATH=$PATH:$SPARK_HOME/bin:$SPARK_HOME/sbin
 * export PYSPARK_PYTHON=python3
 * export PYSPARK_DRIVER_PYTHON=python3
 * source ~/.bashrc

 - Verifica se o Spark está iniciando corretamente
 * spark-shell

 - Agora vamos instalar o spark no airflow
 * pip install pyspark
