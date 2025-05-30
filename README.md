# MkDocs Blog Template

A clean, modern blog template built with MkDocs and Material theme. This template provides a solid foundation for creating beautiful static websites and blogs with markdown content.

## Features

- **Modern Design**: Built with Material Design principles using Material for MkDocs theme
- **Responsive**: Mobile-friendly layout that looks great on all devices
- **Dark/Light Mode**: Automatic theme switching based on user preference
- **Fast Search**: Built-in search functionality with live results
- **SEO Friendly**: Optimized for search engines with proper meta tags
- **Easy Deployment**: One-command deployment to GitHub Pages
- **Markdown Support**: Write content in markdown with extended syntax support
- **Code Highlighting**: Syntax highlighting for multiple programming languages
- **Navigation**: Clean navigation with tabs and sections
- **Social Integration**: Ready-to-configure social media links

## Site Structure

```
├── docs/
│   ├── index.md              # Homepage
│   ├── about.md              # About page
│   └── writing/
│       ├── index.md          # Writing section index
│       └── posts/
│           └── first-post.md # Sample blog post
├── mkdocs.yml               # Site configuration
├── requirements.txt         # Python dependencies
├── .gitignore              # Git ignore rules
├── MANUAL.md               # Detailed setup guide
└── README.md               # This file
```

## Quick Start

### Prerequisites

- Python 3.8+
- Git
- Text editor

### Local Development

1. **Clone or download this template**
   ```bash
   git clone <repository-url>
   cd mkdocs-blog-template
   ```

2. **Create and activate virtual environment**
   ```bash
   python -m venv mkdocs-env
   source mkdocs-env/bin/activate  # Linux/Mac
   # or
   mkdocs-env\Scripts\activate     # Windows
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Start development server**
   ```bash
   mkdocs serve
   ```

5. **Open your browser**
   Navigate to `http://127.0.0.1:8000`

### Customization

1. **Update site information** in `mkdocs.yml`:
   - Change `site_name`, `site_description`, `site_author`
   - Update `site_url` to your GitHub Pages URL
   - Modify social links in the `extra` section

2. **Customize content**:
   - Edit `docs/index.md` for your homepage
   - Update `docs/about.md` with your information
   - Add your blog posts to `docs/writing/posts/`
   - Modify navigation in `mkdocs.yml` as needed

3. **Personalize theme**:
   - Change colors in the `theme.palette` section
   - Enable/disable features in `theme.features`
   - Add custom CSS/JS if needed

## Deployment to GitHub Pages

### Method 1: Automatic Deployment (Recommended)

1. **Create GitHub repository**
   - Create a new repository on GitHub
   - Push your code to the repository

2. **Deploy with MkDocs**
   ```bash
   mkdocs gh-deploy
   ```

3. **Access your site**
   Your site will be available at `https://username.github.io/repository-name`

### Method 2: GitHub Actions (Advanced)

Create `.github/workflows/deploy.yml` for automatic deployment on every push to main branch.

### Custom Domain Setup

1. **Purchase domain** from any registrar
2. **Add CNAME file** to `docs/` directory with your domain name
3. **Configure DNS** at your registrar to point to GitHub Pages
4. **Enable custom domain** in GitHub repository settings

## Content Management

### Writing Blog Posts

1. Create new markdown file in `docs/writing/posts/`
2. Use descriptive filename: `my-awesome-post.md`
3. Add frontmatter and content
4. Update navigation in `mkdocs.yml` if needed

### Markdown Features

This template supports extended markdown syntax:

- **Admonitions**: Call-out boxes for notes, warnings, tips
- **Code blocks**: Syntax highlighting for 100+ languages
- **Tables**: Responsive table formatting
- **Task lists**: Interactive checkboxes
- **Footnotes**: Reference-style footnotes
- **Abbreviations**: Hover definitions

### Adding Pages

1. Create new `.md` file in `docs/` directory
2. Add page to navigation in `mkdocs.yml`
3. Link to page from other content

## Development Commands

```bash
# Start development server
mkdocs serve

# Build static site
mkdocs build

# Deploy to GitHub Pages
mkdocs gh-deploy

# Install new plugin
pip install plugin-name
pip freeze > requirements.txt
```

## File Organization Tips

- Keep posts in `docs/writing/posts/` with descriptive filenames
- Use subdirectories for different content types
- Add images to `docs/assets/images/`
- Keep navigation simple and intuitive
- Use consistent naming conventions

## Troubleshooting

### Common Issues

- **Site not updating**: Clear browser cache or use incognito mode
- **Build errors**: Check YAML syntax in `mkdocs.yml`
- **Missing dependencies**: Ensure virtual environment is activated
- **Navigation issues**: Verify file paths in `mkdocs.yml`

### Getting Help

- Check [MANUAL.md](MANUAL.md) for detailed setup instructions
- Review [MkDocs documentation](https://www.mkdocs.org/)
- Visit [Material theme docs](https://squidfunk.github.io/mkdocs-material/)
- Search GitHub issues for common problems

## Contributing

1. Fork the repository
2. Create feature branch
3. Make your changes
4. Test locally with `mkdocs serve`
5. Submit pull request

## License

This template is open source and available under the MIT License.

## Credits

- Built with [MkDocs](https://www.mkdocs.org/)
- Styled with [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/)
- Hosted on [GitHub Pages](https://pages.github.com/)
- Inspired by modern documentation sites and technical blogs
- Browse more themes at [MkDocs Theme Gallery](https://github.com/mkdocs/mkdocs/wiki/MkDocs-Themes)

---

**Ready to start blogging?** Follow the Quick Start guide above and you'll have your site running in minutes!