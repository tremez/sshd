## sshd Image

Image based on ubuntu 16:04 and provides basic sshd

## Run

	docker run -d -p <PORT>:22 --name sshd tremez/sshd

## Update root password

	docker exec -it sshd /bin/sh -c "echo 'root:PASSWORD' | chpasswd"


