link to repository https://github.com/hjing2/BSBTassignment1.git

Instruction for running

build image
docker build . -t "haodan-coding-assignment1:v1.0"

run application container
docker run --name haodan_container_assignment1 -dp 7775:7775 haodan-coding-assignment1:v1.0
