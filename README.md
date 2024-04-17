```markdown
package main

import (
 "fmt"
)

type SoftwareEngineer struct {
 Name         string
 Role         string
 LanguageSpoken []string
}

func (se *SoftwareEngineer) HelloEveryone() string {
 return fmt.Sprintf("I’m %s 🎓 and I’m a %s 💻. Welcome to my github profile 🕵️!", se.Name, se.Role)
}

func main() {
 me := SoftwareEngineer{
  Name:         "Egor",
  Role:         "Golang Developer",
  LanguageSpoken: []string{"RUS", "EN"},
 }

 fmt.Println(me.HelloEveryone())
}
```
   [![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=EgrShishov&layout=compact&theme=white)](https://github.com/EgrShishov/github-readme-stats)
<h3>For my educational purposes i use C#, C++ and Python.</h3>
