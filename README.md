```markdown
namespace ProfileGitHub;

public class SoftwareEngineer
{
 private string Name { get; set; } = "Egor";

 private string Role { get; set; } = "Intern .NET Developer";

 private List<string> Language_Spoken { get; set; } = new() { "RUS", "EN" };

 public string Hello_Everyone() => @$"I’m {Name} 🎓 and I’m a {Role} 💻. Welcome to my github profile 🕵️!";
}
internal class Program
{
 static void Main(string[] args)
 {
  SoftwareEngineer Me = new();
  Me.Hello_Everyone();
 }
}
```
   [![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=EgrShishov&layout=compact&theme=white)](https://github.com/EgrShishov/github-readme-stats)
<h3>For my educational purposes i use C#, C++ and Python.</h3>
