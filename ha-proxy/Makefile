all: build run

build:
	docker build -t rossey-haproxy-lb .

run:
	docker run -d -p 8080:8080 -p 8081:8081 --rm --name haproxy-lb rossey-haproxy-lb
