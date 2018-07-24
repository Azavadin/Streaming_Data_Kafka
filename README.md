# Processing a stream of data using Kafka

(a) generate.cpp:-
To run this program, use the following command: -
g++ -std=c++11 -o generate generate.cpp
./generate


(b) SimpleProducer.java:-
To run this program, use the following command: -
javac -cp "<path to kafka>/libs/*" "<path to file inside kafka>SimpleProducer.java" java -cp "<path to kafka>/libs/*": . SimpleProducer
  
  
(c) SimpleConsumer.java:-
Run this program in three different terminals:-
javac -cp "<path to kafka>/libs/*" "<path to file inside kafka>SimpleConsumer.java" java -cp "<path to kafka>/libs/*": . SimpleConsumer Topic-1
java -cp "<path to kafka>/libs/*": . SimpleConsumer Topic-2
java -cp "<path to kafka>/libs/*": . SimpleConsumer Topic-3
