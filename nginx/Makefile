all: build run

build:
	docker build -t rossey-nginx-lb .

run:
	docker run -d -p 80:80 --rm --name nginx-lb rossey-nginx-lb
