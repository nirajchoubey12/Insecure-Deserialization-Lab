sudo docker image build -t old_system . 

sudo docker container run -it --publish 8081:8080 old_system


Access http://127.0.0.1:8081/old_system/ 

writeup : https://github.com/voidfyoo/rwctf-2021-old-system/tree/main/writeup
