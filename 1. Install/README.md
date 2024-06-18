Installing GO di Win10 :
1. Download installer : https://golang-id.org/doc/install/
2. Environment Variables (Control panel) ubah ke directory install go, contoh : C:\Program Files\Go\bin

![image](https://github.com/iansaviour/latihanGo/assets/12025576/07c14dba-481b-4afe-adcb-1bdab880a35e)

4. Testing hello world, buat folder, create hello.go :
```
package main

import "fmt"
  
func main() {
    fmt.Printf("hello, world\n")
}
```
5. Buka terminal :
```
go build hello.go
```
7. Di terminal ketik :
```
./hello
```
9. Muncul hello world berarti sudah ok.

