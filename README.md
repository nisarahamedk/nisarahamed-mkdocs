# Portfolio Website with MkDocs Material

This repository provides a template for creating a professional freelance portfolio website using MkDocs Material. Originally designed for technical documentation, MkDocs Material has evolved into a [powerful framework](https://squidfunk.github.io/mkdocs-material/blog/2024/08/19/how-were-transforming-material-for-mkdocs/) that's perfect for portfolios, blogs, and personal websites - all manageable through simple Markdown and YAML files.

## Why MkDocs Material?

- **Quick Setup**: Get your site running in minutes
- **Markdown-Based**: Write content in simple Markdown
- **Code-Friendly**: Built-in syntax highlighting and code blocks
- **Responsive Design**: Looks great on all devices
- **No Frontend Skills Needed**: Professional design out of the box
- **SEO Optimized**: Built-in SEO features
- **Search Functionality**: Full-text search included
- **Social Cards**: Auto-generated preview cards for social media sharing
- **Dark Mode**: Automatic dark/light theme switching

As you go through this setup, please find all the most up to date information in the [official documentation here](https://squidfunk.github.io/mkdocs-material/getting-started/).

## Quick Start
1. **Download & Install Docker Desktop**
https://docs.docker.com/get-started/get-docker/

2. **Clone this repository**
   ```bash
   git clone https://github.com/data-freelancer-mastermind/mkdocs-website-template.git
   cd mkdocs-website-template
   ```

3. **Start the server**
   ```bash
   chmod +x start_server.sh
   ./start_server.sh
   ```
   Visit `http://localhost:8000` to see your site.

## Customizing Your Portfolio

### 1. Basic Configuration

Edit `mkdocs.yml` to customize your site:

- Site name and metadata
- Navigation structure
- Color scheme and fonts
- Custom CSS settings in `stylesheets/extra.css`
- Social links
- Extensions and plugins

### 2. Content Structure

```bash
docs/
├── index.md # Your homepage
├── about.md # About page
├── portfolio/ # Your work
├── blog/ # Blog posts
└── assets/ # Images and other files
```

## Deployment

I recommend publishing your site with GitHub Pages. If you want to keep your repo private, you need a GitHub Pro subscription. Public repos can be deployed with a free GitHub account.

1. Push your repository to GitHub
2. Follow the instructions here: [Publishing your site](https://squidfunk.github.io/mkdocs-material/publishing-your-site/)
3. Set up the GitHub actions for your project
4. Test the deployment by pushing changes

### Custom Domain



1. Add a `CNAME` file in your `docs` folder with your domain
2. Go to `repository/settings/pages` and check the domain settings
3. Follow the [instructions here](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site) to configure your domain and DNS settings
4. GitHub recently changed the DNS linking process: Let me know if we need to update these docs!
5. Also enable HTTPS on this page

## Useful Resources

- [Official MkDocs Material Documentation](https://squidfunk.github.io/mkdocs-material/getting-started/)
- [Icons and Emojis Reference](https://squidfunk.github.io/mkdocs-material/reference/icons-emojis/)
- [Blog Setup Guide](https://squidfunk.github.io/mkdocs-material/blog/)
- [Social Cards Configuration](https://squidfunk.github.io/mkdocs-material/plugins/requirements/image-processing/)
