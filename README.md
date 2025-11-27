# EmiraLabs Open Source Tools

A curated collection of free, powerful open source tools designed to supercharge your development workflow and make complex tasks simple. This site is built using [stw](https://github.com/lithammer/stw), a static site generator.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-os.emiralabs.com-blue)](https://os.emiralabs.com)

## 🚀 Features

### CIDR Calculator
Calculate network details from IP addresses and subnet masks. Perfect for network planning and troubleshooting.

### SLO Calculator
Calculate Service Level Objectives and error budgets. Understand uptime requirements and allowed downtime.

### QR Code Generator
Generate QR codes instantly from text, URLs, or any content. Perfect for sharing information quickly.

## 📁 Project Structure

- `pages/`: Contains the HTML pages for each tool and the main index
- `templates/`: Reusable templates and components (base.html, header, footer, etc.)
- `assets/`: CSS, JS, and images
- `config.yaml`: Site configuration for stw

## 🛠️ Getting Started

### Prerequisites
- [stw](https://github.com/lithammer/stw) (static site generator)
- A web browser

### Running Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/EmiraLabs/os.git
   cd os
   ```

2. Install stw:
   ```bash
   go install github.com/lithammer/stw@latest
   ```

3. Serve the site:
   ```bash
   stw serve
   ```

4. Open your browser and navigate to the provided URL (usually `http://localhost:8080`)

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-tool`)
3. Commit your changes (`git commit -m 'Add amazing tool'`)
4. Build and test locally: `stw serve`
5. Push to the branch (`git push origin feature/amazing-tool`)
6. Open a Pull Request

### Adding a New Tool

To add a new tool to the collection:

1. Create a new directory under `pages/` (e.g., `pages/new-tool/`)
2. Add an `index.html` file with frontmatter metadata and your tool's HTML implementation
3. Update `pages/index.html` to include your tool in the tools grid
4. Run `stw serve` to build and preview the site
5. Test locally and submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🌐 Live Site

Visit [os.emiralabs.com](https://os.emiralabs.com) to use the tools online.

## 📞 Contact

- Website: [emiralabs.com](https://emiralabs.com)
- GitHub: [EmiraLabs](https://github.com/EmiraLabs)

---

Built with ❤️ by [EmiraLabs](https://emiralabs.com)