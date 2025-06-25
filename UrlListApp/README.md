# UrlListApp

UrlListApp is an ASP.NET Core Razor Pages web application designed as the foundation for "The Urlist" website, based on the requirements in `../prd.md`.

## How It Works

```mermaid
flowchart TD
    A[User visits UrlListApp in browser] --> B[Home Page (Index)]
    B --> C[User creates or selects a URL list]
    C --> D[Add/Edit/Delete URLs in the list]
    D --> E[Save or Publish List]
    E --> F[Get sharable link for the list]
    F --> G[Others can view the list via shared link]
```

- **Home Page:** Displays a welcome message and basic navigation.
- **Privacy Page:** Standard privacy policy page.
- **Layout:** Uses Bootstrap for responsive design and a modern look.
- **Ready for Expansion:** The app is scaffolded for you to implement features such as creating, viewing, editing, and sharing URL lists.

## Planned Features (from `../prd.md`)
- Create, edit, and delete URL lists
- Add, edit, and remove URLs in a list
- Custom and automatic list URLs
- Publish and share lists
- View all your lists and delete them

## Getting Started
1. Open the solution in Visual Studio Code or your preferred .NET IDE.
2. Restore dependencies and build the solution:
   ```bash
   dotnet restore
   dotnet build
   ```
3. Run the app:
   ```bash
   dotnet run --project UrlListApp/UrlListApp.csproj
   ```
4. Open your browser to the indicated URL (usually https://localhost:5001 or similar).

## Project Structure
- `Pages/` - Razor Pages for the UI
- `wwwroot/` - Static files (CSS, JS, images)
- `appsettings.json` - App configuration

## Contributing
This project is intended for learning and experimentation during the GitHub Copilot Bootcamp. Feel free to fork, extend, and experiment!

---

For more details on the overall solution, see the root `README.md` and `../prd.md` for requirements.
