# 🌐 DanielClements.com

Welcome to the repository for my personal website, [danielclements.com](https://danielclements.com). This site is built using [Hugo](https://gohugo.io/), a fast and modern static site generator, and styled with the minimalist [Hermit-V2 theme](https://github.com/1bl4z3r/hermit-V2). It is deployed seamlessly using [Cloudflare Pages](https://pages.cloudflare.com/).

---

## 📸 Screenshot

![Website Screenshot](assets/images/screenshot.png)

---

## 🚀 Features

- **Minimalist Design**: Clean, content-focused layout with responsive design.
- **Dark Mode**: Built-in support for light and dark themes.
- **Fast and Secure**: Deployed on Cloudflare Pages for speed and reliability.
- **Customizable**: Easily extendable with Hugo's flexible templating system.

---

## 🛠️ Tech Stack

| **Technology**   | **Description**                                                                 |
|-------------------|---------------------------------------------------------------------------------|
| [Hugo](https://gohugo.io/) | Static site generator for fast and modern websites.                          |
| [Hermit-V2 Theme](https://github.com/1bl4z3r/hermit-V2) | Minimalist theme for Hugo with a focus on content.                  |
| [Cloudflare Pages](https://pages.cloudflare.com/) | Static site hosting with global CDN and HTTPS support.              |
| [Markdown](https://www.markdownguide.org/) | Content is written in Markdown for simplicity and portability.       |

---

## 🏗️ Local Development

### Prerequisites
- [Hugo Extended](https://gohugo.io/getting-started/installing/) (version 0.115.3 or newer)
- [Git](https://git-scm.com/)

### Steps to Run Locally

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/iamclements/danielclements.com.git
   cd danielclements.com
   ```

2. **Start the Hugo Development Server**:
   ```bash
   hugo server -D
   ```

3. **View the Site**:
   Open your browser and navigate to [http://localhost:1313](http://localhost:1313).

4. **Build the Site**:
   To generate the static files for deployment:
   ```bash
   hugo --minify
   ```

   The output will be in the `public/` directory.

---

## 🌍 Deployment

This site is automatically deployed to **Cloudflare Pages** whenever changes are pushed to the `main` branch.

### Manual Deployment
If you need to deploy manually:
1. Build the site:
   ```bash
   hugo --minify
   ```
2. Upload the contents of the `public/` directory to your hosting provider.

---

## 📝 Customization

### Configuring the Site
The main configuration file is `config.toml`. You can update the following settings:
- **Site Title**: Update the `title` field.
- **Author Information**: Add your name, bio, and social links.
- **Theme Settings**: Customize the Hermit-V2 theme options.

### Adding Content
To create a new blog post:
```bash
hugo new posts/my-new-post.md
```
Edit the file in `content/posts/my-new-post.md` to add your content.

---

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 🙌 Acknowledgments

- [Hugo](https://gohugo.io/) for the static site generator.
- [Hermit-V2 Theme](https://github.com/1bl4z3r/hermit-V2) for the clean and minimalist design.
- [Cloudflare Pages](https://pages.cloudflare.com/) for fast and reliable hosting.

---

## 📬 Contact

Feel free to reach out if you have any questions or feedback:
- **Website**: [danielclements.com](https://danielclements.com)
- **GitHub**: [iamclements](https://github.com/iamclements)
```