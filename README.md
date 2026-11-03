# bincom-csharp: contactOne

An ASP.NET Core (.NET 10) Razor Pages application featuring a backend endpoint and an interactive frontend UI.

## Features

- **Backend API**: `GET /api/hello` returning JSON response (`Hello World`, timestamp, status).
- **Frontend UI**: Built with ASP.NET Core Razor Pages and Bootstrap 5, automatically fetching and displaying data from the backend API.
- **Interactive Controls**: Includes dynamic re-fetch capability and direct API inspection links.

## Prerequisites

- [.NET 10 SDK](https://dotnet.microsoft.com/)

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/tediyang/bincom-csharp.git
   cd bincom-csharp
   ```

2. **Run the project:**
   ```bash
   dotnet run --project contactOne/contactOne.csproj
   ```

3. **Open in browser:**
   Navigate to the local URL displayed in the terminal (typically `http://localhost:5162`).
