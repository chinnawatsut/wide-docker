# Wide-Docker

# build-docker
~docker build -t {name} .
-t : tty-connection
{name} : name for images
. : path

# run container
~docker run -d -p 50:80 {name}
run : run container from image
-p : mapping port , 50(user port) and 80(container listing port)
	http://0.0.0.0:5050 -> docker:8080


