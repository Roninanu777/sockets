run: server.o client.o
	 clear
	 ./udpserver
	 gnome-terminal
	 ./udpclient

server.o: udpserver.c
		gcc udpserver.c -o udpserver
client.o: udpclient.c
		gcc udpclient.c -o udpclient
server: udpserver.c
		gcc udpserver.c -o udpserver
		./udpserver
client: udpclient.c
		gcc udpclient.c -o udpclient
		./udpclient
clean: 
	rm udpclient udpserver