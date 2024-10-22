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

    public void Hi()
    {
        // Using string interpolation to print variables
        Console.WriteLine($"{Fullname} | {Nickname}");
        Console.WriteLine(Status);  // Corrected from 'status' to 'Status'
        Console.WriteLine(Email);
        Console.WriteLine(LinkedIn); // Corrected from 'Linkedin' to 'LinkedIn'
        Console.WriteLine(Phone);
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
