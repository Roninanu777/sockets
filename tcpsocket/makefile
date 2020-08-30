run: server.o client.o
	 clear
	 ./tcpserver
	 gnome-terminal
	 ./tcpclient

server.o: tcpserver.c
		gcc tcpserver.c -o tcpserver
client.o: tcpclient.c
		gcc tcpclient.c -o tcpclient
server: tcpserver.c
		gcc tcpserver.c -o tcpserver
		./tcpserver
client: tcpclient.c
		gcc tcpclient.c -o tcpclient
		./tcpclient
clean: 
	rm tcpclient tcpserver