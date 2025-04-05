namespace ProfileGitHub;

public class SoftwareEngineer
{
    public required string Name { get; init; } = "Egor";

    public required string Role { get; init; } = "Intern .NET Developer at T-Team Belarus";

    public List<string> LanguagesSpoken { get; init; } = ["RUS", "EN"];
    
    public string Description { get; init; } = "I am passionate about delivering high-quality solutions, leveraging industry best practices, and continuously improving my skills.";

    public string HelloEveryone() => $"""
        I'm {Name} 🎓 and I'm a {Role} 💻. Welcome to my github profile 🕵️!
        {Description}
        """;
}

internal class Program
{
    static void Main(string[] args)
    {
        var me = new SoftwareEngineer();
        Console.WriteLine(me.HelloEveryone());
    }
}
