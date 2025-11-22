```markdown
namespace ProfileGitHub;

public class SoftwareEngineer
{
    public required string Name { get; init; } = "Yahor";

    public required string Surname { get; init; } = "Shyshou";

    public required string Role { get; init; } = "Junior+ .NET Developer at T-Team Belarus";

    public IReadOnlyList<string> LanguagesSpoken { get; init; } = [ "RUS", "EN" ];
    
    public string Description { get; init; } = "I am passionate about delivering high-quality solutions, leveraging industry best practices, and continuously improving my skills.";

    public string SayHello() => $"""
        Hello! I'm {Name} 🎓 and I'm a {Role} 💻. Welcome to my github profile 🕵️!
        {Description}
        """;
}


var me = new SoftwareEngineer();
Console.WriteLine(me.SayHello());

```
