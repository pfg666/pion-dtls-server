# pion-dtls-server
Go DTLS server harness.
The harness was used to test the Pion DTLS server implementation as part of the state fuzzing work published in [USENIX 20][usenix]. 
As we extended the program for clients, we moved development to a [new repository][new-pion].

# Setting up

> git clone https://github.com/pion/dtls.git

> go get github.com/pion/dtls

> go run main/main.go

Alternatively, once can compile and then run the binaries, say:

> go build -o main/main main/main.go 

> main/main


[usenix]:https://www.usenix.org/conference/usenixsecurity20/presentation/fiterau-brostean
[new-pion]:https://github.com/assist-project/pion-dtls-examples
