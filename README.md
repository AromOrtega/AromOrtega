<div align="center">

# Hola, soy Arom Ortega 👋

<a href="https://github.com/AromOrtega">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=800&color=2F81F7&center=true&vCenter=true&width=650&lines=Software+Developer+%40+Glexco+Robotics;Backend+con+.NET+Core+y+C%23;Microservicios+%2B+Docker;Integrando+software+con+robots+reales+%F0%9F%A4%96" alt="Typing SVG" />
</a>

<p>
  <a href="https://www.linkedin.com/in/arom-ortega-177401335"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:aromortega05@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/></a>
  <img src="https://img.shields.io/badge/📍_Perú-D91E18?style=for-the-badge" alt="Perú"/>
  <img src="https://komarev.com/ghpvc/?username=AromOrtega&label=Visitas&color=2F81F7&style=for-the-badge" alt="Visitas"/>
</p>

</div>

---

## 👨‍💻 Sobre mí

```csharp
public class AromOrtega
{
    public string Rol        => "Software Developer @ Glexco Robotics & Automation";
    public string Ubicacion  => "Perú 🇵🇪";
    public string[] Backend  => new[] { "C#", ".NET Core", "SQL Server" };
    public string[] Aprendiendo => new[] { "Microservicios", "CQRS", "Docker", "Arquitectura Limpia" };
    public string Filosofia  => "Código limpio hoy, menos problemas mañana.";
}
🔭 Combino backends sólidos en .NET con hardware robótico real.
🌱 Profundizando en arquitecturas distribuidas y patrones de diseño.
💬 Pregúntame sobre .NET, APIs REST, microservicios o robots de servicio.
🏢 Experiencia
🤖 Software Developer — Glexco Robotics & Automation
Noviembre 2025 – Actualidad

Desarrollo de aplicaciones para el robot humanoide de servicio Cruzr.
Implementación de navegación autónoma, comandos de voz y reconocimiento facial.
Gestión de conexiones ADB y depuración de sistemas embebidos para una comunicación estable entre hardware y aplicación.
🛠️ Stack Tecnológico
<div align="center">
Backend<br>
<img src="https://skillicons.dev/icons?i=cs,dotnet,java,kotlin" />

Bases de datos y DevOps<br>
<img src="https://skillicons.dev/icons?i=mysql,docker,git,github,linux" />
<img src="https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white" height="48" />

Frontend y móvil<br>
<img src="https://skillicons.dev/icons?i=angular,ts,androidstudio" />

Herramientas<br>
<img src="https://skillicons.dev/icons?i=vscode,visualstudio,postman" />

</div>
📁 Proyectos Destacados
Proyecto	Descripción	Tecnologías
🧠 SIAE	Sistema Inteligente de Asistencia Emocional para monitorear la salud mental en instituciones académicas.	.NET SQL Server
🩺 MicroSalud	Backend de salud basado en microservicios con frontend web.	.NET Microservicios Docker
🤖 Cruzr Integration	Navegación autónoma y reconocimiento facial en un robot humanoide real.	Android ADB IA
🐱 Cat Breeds App	App móvil para un refugio: catálogo de razas y proceso de adopción.	Android iOS
🎓 EFSRT Project	Coordinación técnica y gestión de entregables de un proyecto académico.	Gestión Liderazgo
📈 Estadísticas
<div align="center"> <picture> <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=AromOrtega&show_icons=true&theme=tokyonight&hide_border=true&bg_color=00000000&include_all_commits=true&count_private=true" /> <img height="165" src="https://github-readme-stats.vercel.app/api?username=AromOrtega&show_icons=true&theme=default&hide_border=true&include_all_commits=true&count_private=true" alt="GitHub Stats" /> </picture> <picture> <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=AromOrtega&layout=compact&theme=tokyonight&hide_border=true&bg_color=00000000&langs_count=6" /> <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AromOrtega&layout=compact&theme=default&hide_border=true&langs_count=6" alt="Top Languages" /> </picture> <picture> <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com/?user=AromOrtega&theme=tokyonight&hide_border=true&background=00000000" /> <img src="https://streak-stats.demolab.com/?user=AromOrtega&theme=default&hide_border=true" alt="GitHub Streak" /> </picture> </div>
🐍 Contribuciones
<div align="center"> <picture> <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AromOrtega/AromOrtega/output/github-contribution-grid-snake-dark.svg" /> <img src="https://raw.githubusercontent.com/AromOrtega/AromOrtega/output/github-contribution-grid-snake.svg" alt="Snake animation" width="100%" /> </picture> </div>
<div align="center">
🤝 ¿Hablamos?
Siempre abierto a nuevos retos, proyectos y networking.

<a href="mailto:aromortega05@gmail.com"><img src="https://img.shields.io/badge/Contáctame-2F81F7?style=for-the-badge&logo=gmail&logoColor=white" alt="Contáctame"/></a>
<a href="https://www.linkedin.com/in/arom-ortega-177401335"><img src="https://img.shields.io/badge/Conectemos-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>

</div> ```
.github/workflows/snake.yml
Créalo en tu repo de perfil, AromOrtega/AromOrtega:


name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"   # diario
  workflow_dispatch:
  push:
    branches: [main]

permissions:
  contents: write

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
