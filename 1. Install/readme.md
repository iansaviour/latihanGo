Installing GO di Win10 :

Download installer : https://golang-id.org/doc/install/
Environment Variables (Control panel) ubah ke directory install go, contoh : C:\Program Files\Go\bin
image

Testing hello world, buat folder, create hello.go :
package main

import "fmt"
  
func main() {
    fmt.Printf("hello, world\n")
}
Buka terminal :
go build hello.go
Di terminal ketik :
./hello
Muncul hello world berarti sudah ok.
