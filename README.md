# 🤖 Hello there!

I'm Gustavo, a Mexico-based software developer with 15+ years of experience. I'm passionate about building software that helps people and businesses.
<p align="center">
  <img src="https://img.shields.io/badge/AI%20Architect-EE1199?style=for-the-badge&logoColor=white" alt="AI Architect" />
  <img src="https://img.shields.io/badge/CTO%20@%20Ambystech-9932CC?style=for-the-badge&logoColor=white" alt="CTO @ Ambystech" />
  <img src="https://img.shields.io/badge/Monterrey,%20MX-0A0D14?style=for-the-badge&logoColor=white" alt="Monterrey, MX" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/C%23-3C69E7?style=flat-square&logo=csharp&logoColor=white" />
  <img src="https://img.shields.io/badge/.NET%209-3C69E7?style=flat-square&logo=dotnet&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3C69E7?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3C69E7?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Azure-00CCFF?style=flat-square&logo=microsoftazure&logoColor=0A0D14" />
  <img src="https://img.shields.io/badge/AI--102%20Certified-00CCFF?style=flat-square&logo=microsoft&logoColor=0A0D14" />
  <img src="https://img.shields.io/badge/Neo4j-00CCFF?style=flat-square&logo=neo4j&logoColor=0A0D14" />
  <img src="https://img.shields.io/badge/MCP-EE1199?style=flat-square&logoColor=white" />
  <img src="https://img.shields.io/badge/Claude%20Code-EE1199?style=flat-square&logo=anthropic&logoColor=white" />
</p>
```csharp
using Ambystech.Ai;
using GustavoBarrientos;

namespace Profile;

public sealed record Bio() : AiArchitect
{
    public string Name     => "Gustavo Barrientos";
    public string Title    => "AI Architect · Co-Founder & CTO @ Ambystech";
    public string Location => "Monterrey, Nuevo León, México";

    public Uri Blog       => new("https://www.barrientos.io");
    public Uri Ambystech  => new("https://www.ambystech.com");
    public Uri OpenSource => new("https://www.ambystech.io");
}

public sealed record Stack() : AiArchitect
{
    public string[] Languages  => ["C#", "TypeScript", "Python"];
    public string[] Frameworks => [".NET 9", "ASP.NET Core", "Angular", "Astro"];
    public string[] Data       => ["MSSQL", "CosmosDB", "Neo4j", "Qdrant"];
    public string[] Cloud      => ["Azure AI Foundry", "Container Apps", "Functions", "Service Bus", "AKS"];

    public AiPlatform Ai => new()
    {
        Protocols = ["MCP", "A2A"],
        Patterns  = ["Multi-agent", "RAG", "Spec-Driven Development"],
        Tools     = ["Claude Code", "OpenCode", "Cursor"]
    };
}

public sealed record OpenSource() : AiArchitect
{
    public Project[] Projects =>
    [
        new("Elaris.UI",         "True-color terminal UI for .NET"),
        new("Neo4j.Repository",  "Generic repository pattern for Neo4j"),
        new("AmbyKit",           "Spec-driven development for AI coding agents")
    ];

    public string License => "MIT, always.";
    public Uri Org        => new("https://github.com/ambystechcom");
}

public readonly record struct Project(string Name, string About);
```


![.NET](https://img.shields.io/badge/.Net-430098?style=for-the-badge&logo=.net&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-338eef?style=for-the-badge&logo=azure&logoColor=white)
![Github](https://img.shields.io/badge/Github-000000?style=for-the-badge&logo=github&logoColor=white)



![Gustavo's GitHub stats](https://github-readme-stats.vercel.app/api?username=tavobarrientos&show_icons=true&theme=holi) 
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=tavobarrientos&langs_count=4&layout=compact)

## 📫 Let’s connect
- 💼 [LinkedIn](https://www.linkedin.com/in/gustavo-barrientos)  
- 🌐 [ambystech.com](https://www.ambystech.com)  
- 📝 [barrientos.io](https://barrientos.io)  
- ✉️ gustavo.barrientos@ambystech.com  
