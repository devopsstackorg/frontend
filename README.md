$git clone https://github.com/devopsstackorg/frontend.git

$cd frontend

$docker image build -t <image_name> .

$docker container run -d --name <container_name> -p 80:80 <image_name>
