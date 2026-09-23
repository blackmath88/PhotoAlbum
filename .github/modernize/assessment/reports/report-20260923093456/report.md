# PhotoAlbum

## Summary

| Metric | Value |
|--------|-------|
| Total Issues | 8 |
| Mandatory Blockers | 1 |
| Potential Issues | 4 |

## Component Information

| Property | Value |
|----------|-------|
| Language | C# |
| Frameworks | net9.0 |
| Build tools | MSBuild |

## Cloud Readiness Issues

| Issue Name | Criticality | Story Points | Occurrences |
|------------|-------------|--------------|-------------|
| Windows-Authentifizierung erkannt | Mandatory | 3 | [1](#Windows-Authentifizierung_erkannt) |
| Es wurden lokale oder Netzwerk-E/A-Vorgänge erkannt. | Potential | 3 | [12](#Es_wurden_lokale_oder_Netzwerk-E_A-Vorgänge_erkannt) |
| Local application configuration detected | Potential | 1 | [3](#Local_application_configuration_detected) |
| SQL-Datenbankverbindung erkannt | Potential | 3 | [1](#SQL-Datenbankverbindung_erkannt) |
| Verbindungszeichenfolge wurde erkannt | Potential | 3 | [1](#Verbindungszeichenfolge_wurde_erkannt) |
| Hartcodierte vertrauliche Daten erkannt | Optional | 3 | [2](#Hartcodierte_vertrauliche_Daten_erkannt) |
| Statischer Inhalt erkannt | Optional | 3 | [1](#Statischer_Inhalt_erkannt) |
| Verbindungszeichenfolgen ohne Konfigurations-Generatoren erkannt | Optional | 3 | [1](#Verbindungszeichenfolgen_ohne_Konfigurations-Generatoren_erkannt) |

### Issue Details

<details id="Windows-Authentifizierung_erkannt">
<summary><b>Windows-Authentifizierung erkannt</b> — affected files</summary>

- `PhotoAlbum/Web.config`

</details>

<details id="Es_wurden_lokale_oder_Netzwerk-E_A-Vorgänge_erkannt">
<summary><b>Es wurden lokale oder Netzwerk-E/A-Vorgänge erkannt.</b> — affected files</summary>

- `PhotoAlbum/Program.cs (line 41, col 4)`
- `PhotoAlbum/Program.cs (line 39, col 5)`
- `PhotoAlbum/Pages/PhotoFile.cshtml.cs (line 60, col 27)`
- `PhotoAlbum/Pages/PhotoFile.cshtml.cs (line 66, col 44)`
- `PhotoAlbum/Pages/PhotoFile.cshtml.cs (line 58, col 40)`
- `PhotoAlbum/Services/PhotoService.cs (line 149, col 16)`
- `PhotoAlbum/Services/PhotoService.cs (line 200, col 24)`
- `PhotoAlbum/Services/PhotoService.cs (line 243, col 20)`
- `PhotoAlbum/Services/PhotoService.cs (line 147, col 17)`
- `PhotoAlbum/Services/PhotoService.cs (line 198, col 24)`
- `PhotoAlbum/Services/PhotoService.cs (line 241, col 20)`
- `PhotoAlbum/Services/PhotoService.cs (line 157, col 39)`

</details>

<details id="Local_application_configuration_detected">
<summary><b>Local application configuration detected</b> — affected files</summary>

- `PhotoAlbum/appsettings.json`

</details>

<details id="SQL-Datenbankverbindung_erkannt">
<summary><b>SQL-Datenbankverbindung erkannt</b> — affected files</summary>

- `PhotoAlbum/Web.config`

</details>

<details id="Verbindungszeichenfolge_wurde_erkannt">
<summary><b>Verbindungszeichenfolge wurde erkannt</b> — affected files</summary>

- `PhotoAlbum/appsettings.json`

</details>

<details id="Hartcodierte_vertrauliche_Daten_erkannt">
<summary><b>Hartcodierte vertrauliche Daten erkannt</b> — affected files</summary>

- `PhotoAlbum/Pages/Login.cshtml.cs (line 55, col 27)`
- `PhotoAlbum/Pages/Login.cshtml.cs (line 42, col 43)`

</details>

<details id="Statischer_Inhalt_erkannt">
<summary><b>Statischer Inhalt erkannt</b> — affected files</summary>

- `PhotoAlbum/PhotoAlbum.csproj`

</details>

<details id="Verbindungszeichenfolgen_ohne_Konfigurations-Generatoren_erkannt">
<summary><b>Verbindungszeichenfolgen ohne Konfigurations-Generatoren erkannt</b> — affected files</summary>

- `PhotoAlbum/Web.config`

</details>

## DotNET Upgrade Issues [View Details](scenarios/dotnet-version-upgrade/assessment.md)

| Issue Category | Criticality | Story Points |
|----------------|-------------|--------------|
| Binär inkompatibel mit ausgewählter .NET-Version | Mandatory | 1 |
| Die Zielframeworks des Projekts müssen geändert werden | Mandatory | 1 |
| Ein NuGet-Paketupgrade wird empfohlen | Potential | 1 |
| Verhaltensänderung bei ausgewählter .NET-Version | Potential | 1 |
| Das NuGet-Paket ist veraltet | Optional | 1 |

### Issue Details

<details>
<summary><b>Binär inkompatibel mit ausgewählter .NET-Version</b> — affected files</summary>

- `PhotoAlbum/Services/PhotoService.cs (line 35, col 8)`
- `PhotoAlbum/Program.cs (line 45, col 0)`

</details>

<details>
<summary><b>Die Zielframeworks des Projekts müssen geändert werden</b> — affected files</summary>

- `PhotoAlbum/PhotoAlbum.csproj`
- `PhotoAlbum.Tests/PhotoAlbum.Tests.csproj`

</details>

<details>
<summary><b>Ein NuGet-Paketupgrade wird empfohlen</b> — affected files</summary>

- `PhotoAlbum/PhotoAlbum.csproj`
- `PhotoAlbum.Tests/PhotoAlbum.Tests.csproj`

</details>

<details>
<summary><b>Verhaltensänderung bei ausgewählter .NET-Version</b> — affected files</summary>

- `PhotoAlbum/Program.cs (line 65, col 4)`

</details>

<details>
<summary><b>Das NuGet-Paket ist veraltet</b> — affected files</summary>

- `PhotoAlbum.Tests/PhotoAlbum.Tests.csproj`

</details>

---

## Codebase Insights

> **Note:** These documents are generated by AI and may contain inaccuracies or incomplete information. Please review carefully.

> **Codebase Insights aren't available yet.**
>
> These documents are generated when assessment runs with **Full analysis** coverage. Re-run the assessment and set `analysisCoverage: full` to enable them.

[Share feedback](https://aka.ms/ghcp-appmod/feedback)
