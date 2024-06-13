```csharp
using System;

class SoftwareEngineer
{
    public string Fullname { get; set; } = "Ziya Mammadov";
    public DateTime DateOfBirth { get; set; } = new DateTime(2008, 5, 24);
    public string Nickname { get; set; } = "zmmmdf";
    public string Status { get; set; } = "Learning to code";
    public string Email { get; set; } = "ziyamm08@gmail.com";
    public string LinkedIn { get; set; } = "linkedin.com/in/mziya/";
    public string[] ProgrammingLanguages { get; set; } = { "C#", "C++", "Python", "PHP" };
    public string[] SpokenLanguages { get; set; } = { "Azerbaijani", "English", "Turkish" };
    public string Phone { get; set; } = "+994 010 515 05 24";

    public void DisplayPersonalInfo()
    {
        Console.WriteLine($"Hi, I'm {Fullname} ({Nickname}). I am currently {Status}.");
        Console.Write("I'm proficient in the following programming languages: ");
        Console.WriteLine(string.Join(", ", ProgrammingLanguages));
        Console.Write("I speak the following languages: ");
        Console.WriteLine(string.Join(", ", SpokenLanguages));
    }

    public void DisplayContactInfo()
    {
        Console.WriteLine($"📫 You can reach me at {Email}.");
        Console.WriteLine($"📞 My phone number is {Phone}.");
        Console.WriteLine($"🔗 LinkedIn: {LinkedIn}");
    }

    public void DisplayEducation()
    {
        Console.WriteLine("EDUCATION");
        Console.WriteLine("Republican Humanitarian Gymnasium named after S.J. Pishevari");
        Console.WriteLine("Sep 2019 - Present");
        Console.WriteLine("Secondary school №326");
        Console.WriteLine("Sep 2014 - June 2019");
    }

    public void DisplayAdditionalInfo()
    {
        Console.WriteLine("ADDITIONAL INFORMATION");
        Console.WriteLine("Technical Skills: Version control, Python, OOP, SQL, Docker,");
        Console.WriteLine("Web scraping, CI/CD, Competitive programming, Package managers");

        Console.WriteLine("Interpersonal Skills: Communication, Negotiation, Strategic planning,");
        Console.WriteLine("Analytical thinking, Team leadership, Analysis");

        Console.WriteLine("Awards: Republican Informatics Olympiad Medal");
        Console.WriteLine("by Ministry of Science and Education, Republic of Azerbaijan");
    }

    public void Hi()
    {
        me.DisplayPersonalInfo()
        me.DisplayContactInfo();
        me.DisplayEducation();
        me.DisplayAdditionalInfo();
    }
}

class Program
{
    static void Main(string[] args)
    {
        SoftwareEngineer me = new SoftwareEngineer();
        me.Hi();
    }
}

```

<br/>
<img align="right" alt="Coding" width="400" src="https://flow.org/img/featurette-faster.gif">
<p align="left">
<img src="https://komarev.com/ghpvc/?username=zmmmdf&label=Profile%20views&color=3EB810&style=flat" alt="drongo-j" />
</p>
- 👨‍💻 Visit Website [zmmmdf.xyz](https://zmmmdf.xyz)
