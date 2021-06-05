<h2 align="center"><b>Hello!! 👋🏻 developers, I'm a web developer I like to learn new website technology.</b></h2>

```go
package main
  
import (
	"fmt"
	"strings"
	"time"
)

func main() {
    Loading()
    Header()
    Body()
    Footer()
}

func Header() {
	//Header
Header := `
_____ MainHeader _____
Hello developers, I'm a web developer.
I like to learn new website technology.
Have fun with my git.

`
	fmt.Printf(Header)
}

//Load Info
func Loading() {
	const col = 20

	bar := fmt.Sprintf("\x0c[%%-%vs]", col)
	for i := 0; i < col; i++ {
		fmt.Printf(bar, strings.Repeat("=", i)+">")
		time.Sleep(40 * time.Millisecond)
	}
	fmt.Printf(bar+" Done!", strings.Repeat("=", col))
}

//About me
func Body() {
	//Header
	HeaderBody := "_____About me_____"

	//Info
	First_name := "Kongthap";
	Last_name := "phuengsang";
	Nickname := "Folk";
	Birthday := "25 Jan 48";
	Age := 16;
	
	//Print Info
	fmt.Printf("%s \n",HeaderBody)
	fmt.Printf("Name: %s %s\nNickname: %s \nBirthday : %s\n",First_name,Last_name,Nickname,Birthday)
	fmt.Printf("Age: %d\n",Age)
	
	languages := [5]string{"JavaScript", "GO", "PHP", "Python", "C"}
	stylesheets := [2]string{"CSS", "Bootstrap"}
	frameworks := [1]string{"React"} 
	runtimes:= [1]string{"Node"}
	databases:= [2]string{"MySQL", "MariaDB"}
	
	fmt.Printf("Languages : %v\nStylesheets : %v\nFrameworks : %v\n",languages,stylesheets,frameworks)
	fmt.Printf("Runtimes : %v\nDatabases : %v\n",runtimes,databases)
	
}

//Contact me
func Footer() {
	//Header
	HeaderFooter := "_____Contact me_____"
	//Info
	Facebook := "Kongthap phuengsang";
	Mail := "sisoopth@hotmail.com";
	Discord := "ᴋᴇᴀ#8184";
	Github := "Kongthap-code"
  	Instagram := "kp_98ps"
	Telephone_number := "+66 83-2310639";
	
	//Print Info
	fmt.Printf("%s \n",HeaderFooter)
	fmt.Printf("Facebook: %s \nMail: %s \nDiscord : %s\nTelephone_number : %s\n",Facebook,Mail,Discord,Telephone_number)
	fmt.Printf("Github: %s \nInstagram : %s\n",Github,Instagram)
	fmt.Printf("Thank you")
}
```
