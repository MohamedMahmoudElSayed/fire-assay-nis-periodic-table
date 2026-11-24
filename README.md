# Fire Assay and NiS Fire Assay Periodic Table

An interactive, responsive 118-element reference for lead fire assay and nickel sulfide fire assay (NiS-FA). The app provides element-specific collection information, common analytical methods, detection limits, and 4K PNG export.

## Features

- Interactive periodic table covering all 118 elements
- Lead fire-assay and NiS fire-assay element classifications
- Element detail panel with method, instrumentation, and typical lower limits of detection
- Search and category filters
- Responsive layout for desktop and mobile browsers
- Downloadable 4K periodic-table PNG
- No build step or external JavaScript dependencies

## Run locally

Open `index.html` directly in a modern browser, or serve the folder with Python:

```powershell
cd fire-assay-nis-periodic-table
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Project structure

```text
.
|-- index.html
|-- README.md
|-- LICENSE
|-- CONTRIBUTING.md
`-- .gitignore
```

## GitHub Pages

After publishing to GitHub, open **Settings > Pages**, select **Deploy from a branch**, choose the repository's default branch and `/ (root)` folder, and save.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).

## Disclaimer

This app is an educational and operational reference. Laboratory methods, reagent quantities, temperatures, and detection limits vary by matrix and accreditation scope. Always verify procedures against validated in-house and applicable standardized methods.
