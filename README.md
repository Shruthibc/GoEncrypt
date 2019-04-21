# go-encrypt

* Accepts a string input of up to 250 characters and generates a signature using the SHA256 digest of the input. 
* Prints the original input, the signature, and a public key that may be used to verify the signature. 
* The function will terminate if a string longer than 250 characters is provided.

Program Flow : 
--------------------------
- main.go 
- signature/signature.go -  Generates a signature using the provided RSA key and the SHA256 digest of the input.
- signature/key.go  - Generates the Random key ( public-private key-pair)

Execution :
--------------------------
-- go build main.go
-- main abc@xyz.com


Go-Test package :
--------------------------
// to test the code 

-- go test -v ./...


