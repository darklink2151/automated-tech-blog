# Tech Automation Hub

Automated tech blog built with Hugo and deployed on Netlify.

## Quick Start

### Local Development

```bash
# Install Hugo (Windows)
winget install Hugo.Hugo.Extended

# Clone this repository
git clone https://github.com/yourusername/automated-tech-blog.git
cd automated-tech-blog

# Start development server
hugo server -D

# Visit http://localhost:1313
```

### Create New Post

```bash
hugo new content/posts/my-new-post.md
```

### Build for Production

```bash
hugo --gc --minify
```

## Deployment

### Netlify (Recommended)

1. Push to GitHub
2. Connect Netlify to your GitHub repo
3. Netlify will auto-deploy on every push

### Manual Deployment

```bash
hugo --gc --minify
# Upload /public folder to your host
```

## Configuration

Edit `hugo.toml` to customize:
- Site title and description
- Social media links
- Google Analytics
- Author information

## Content Structure

```
content/
├── posts/          # Blog posts
├── about.md        # About page
└── _index.md       # Homepage content
```

## Theme

Using [PaperMod](https://github.com/adityatelange/hugo-PaperMod) - fast, SEO-friendly, feature-rich.

## License

Content: CC BY 4.0
Code: MIT

## Contact

- Website: [your-blog.netlify.app]
- Email: contact@yourdomain.com

---

Built with ❤️ using Hugo and automated with AI
