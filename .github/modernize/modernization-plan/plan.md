# Modernization Plan: .NET 10 Upgrade

**Project**: PhotoAlbum

---

## Technical Framework

- **Language**: C# on .NET 9
- **Framework**: ASP.NET Core Razor Pages
- **Build Tool**: dotnet SDK / solution build
- **Database**: SQL Server LocalDB
- **Key Dependencies**: Entity Framework Core, ImageSharp, xUnit

---

## Overview

> This migration upgrades PhotoAlbum to .NET 10. The application currently runs
> on .NET 9 with a matching test project. The new baseline will:
>
> - keep the existing gallery experience on the latest LTS runtime;
> - align the application and tests with a supported .NET 10 target;
> - preserve current behavior while maintaining build and test reliability.
>
> The migration follows a focused framework-only upgrade with no Azure hosting
> or deployment changes.

---

## Migration Impact Summary

| App | Original | New | Auth | Comments |
|-----|----------|-----|------|----------|
| PhotoAlbum | ASP.NET Core 9 | ASP.NET Core 10 | N/A | Runtime only |

