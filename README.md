# Olá! Eu  me chamo Enzo
 
```c#
static void Main(string[] args)
        {
            Desenvolvedor sobreMim = new Desenvolvedor
            {
                Nome = "Enzo Gonçalves Lanzi",
                Trabalho = "Estudande de T.I | Jovem Aprendiz",
                Contato = new List<string>
                {
                    "enzolanzi189@gmail.com",
                    "linkedin.com/in/enzgl/",
                }
                Local = "Americana/SP"
            };

            Skills minhasSkills = new Skills
            {
                Linguagens = new List<string> { "C#", "JavaScript", "PHP", "Python", "HTML", "Css" "SQL"},
            };

            Console.WriteLine("Sobre Mim:");
            Console.WriteLine($"Nome: {sobreMim.Nome}");
            Console.WriteLine($"Área: {sobreMim.Area}");
            Console.WriteLine($"Trabalho: {sobreMim.Trabalho}");
            Console.WriteLine($"Local: {sobreMim.Local}");
            Console.WriteLine("Contato:");
            foreach (var contato in sobreMim.Contato)
            {
                Console.WriteLine(contato);
            }

            Console.WriteLine("\nMinhas Skills:");
            Console.WriteLine("Linguagens:");
            foreach (var linguagem in minhasSkills.Linguagens)
            {
                Console.WriteLine(linguagem);
            }
        }
```
<br>
<div style="display: inline-block;">

![C#](https://img.shields.io/badge/-C%23-333333?style=flat&logo=C%2B%2B&logoColor=00599C)
![JavaScript](https://img.shields.io/badge/-JavaScript-333333?style=flat&logo=javascript)
![HTML5](https://img.shields.io/badge/-HTML5-333333?style=flat&logo=HTML5)
![CSS](https://img.shields.io/badge/-CSS-333333?style=flat&logo=CSS3&logoColor=1572B6)
![MySQL](https://img.shields.io/badge/-MySQL-333333?style=flat&logo=mysql)
![Python](https://img.shields.io/badge/-Python-333333?style=flat&logo=python)
![PHP](https://img.shields.io/badge/PHP-333333?style=flat&logo=php)
![Windows](https://img.shields.io/badge/Windows-333333?style=flat&logo=Windows&logoColor=00599C)

</div>