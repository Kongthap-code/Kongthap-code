### Hi!
```go
package main
  
import "fmt"

func main() {
    Header()
    infouser()
}
  
func Header() {
Header := `Hello! developers, I'm a web developer. 
I like to learn new website technology.
Have fun with my git.

`
    fmt.Printf(Header)
}

func infouser() {
	//Header
	HeaderInfo := "About me"
	//Info
	First_name := "Kongthap"
	Last_name := "phuengsang"
	Nickname := "Folk"
	Birthday := "25 Jan 48"
	Age := 16
	
	//Show Info
	fmt.Printf("%s \n",HeaderInfo)
	fmt.Printf("Name: %s %s\nNickname: %s \nBirthday : %s\n",First_name,Last_name,Nickname,Birthday)
	fmt.Printf("Age: %d\n",Age)
}
```
