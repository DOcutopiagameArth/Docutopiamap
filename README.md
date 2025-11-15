# 📍 Docutopia Map

Docutopia Map is the code base that powers [docutopia.de](https://docutopia.de), a collaborative map and directory for the German documentary film ecosystem. The platform highlights filmmakers, production collectives, festivals, initiatives, resources, and places that support documentary storytelling. It is designed to make the landscape of documentary culture more visible, foster exchange, and help new collaborations emerge.

> **Note**
> This project is a fork of [utopia-map](https://github.com/utopia-os/utopia-map). We extend and adapt the original open-source project to serve the needs of the Docutopia community.

## What you can do with Docutopia Map

- 🔎 **Explore the scene** – Browse a living map of documentary actors across Germany and beyond.
- 🗂️ **Discover thematic layers** – Filter entries by categories like people, projects, events, infrastructures, and learning opportunities.
- 📌 **Navigate interactively** – Click markers to open rich popups with key facts, contacts, and links.
- 🤝 **Build connections** – Find collaborators, venues, or initiatives that align with your interests.
- 🧭 **Stay oriented** – Use search, tagging, and layer descriptions to quickly surface relevant entries.

## Local development

Install dependencies and start the development servers:

```bash
npm install
npm run dev
```

- The frontend runs on [Next.js](https://nextjs.org/) with shared UI components from Utopia UI.
- The backend is a [Strapi](https://strapi.io/) instance that stores layers, items, and media assets.

For more detailed setup instructions, refer to the documentation in the `app/` and `backend/` directories.

## Contributing

Docutopia thrives on contributions from documentary practitioners, researchers, and developers. If you want to propose new features, report bugs, or contribute data to the map, please open an issue or submit a pull request.

When contributing code:

1. Fork the repository or work on a dedicated branch.
2. Follow the coding standards outlined in this repository.
3. Provide clear descriptions, screenshots (when relevant), and tests for your changes.

## Community & Support

- 📬 Email: [info@docutopia.de](mailto:info@docutopia.de)
- 🌐 Website: [docutopia.de](https://docutopia.de)
- 💬 Chat: Reach out via the community channels listed on the website.

## License

Docutopia Map inherits the open-source license of the original project. See [`LICENSE`](LICENSE) for details.

