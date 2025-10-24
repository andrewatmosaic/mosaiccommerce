# TG Site Search Comparison

A comprehensive tool for comparing and analyzing site search functionality across different platforms and implementations.

## 🚀 Quick Start

This project is designed to be hosted on GitHub Pages with a custom domain configuration.

### GitHub Pages Setup

1. **Create a new GitHub repository** named `tg-sitesearch-comparison`
2. **Clone this repository** to your local machine
3. **Push the code** to the main branch
4. **Enable GitHub Pages** in repository settings:
   - Go to Settings → Pages
   - Set source to "Deploy from a branch"
   - Select "main" branch
   - Set folder to "/ (root)"

### Custom Domain Configuration

To host this at `https://tg-sitesearch-comparison.mosaiccommerce.io`:

1. **Add CNAME file** (already included in this repo)
2. **Configure DNS**:
   - Add a CNAME record: `tg-sitesearch-comparison` → `yourusername.github.io`
3. **Update GitHub Pages settings**:
   - In Settings → Pages, add custom domain: `tg-sitesearch-comparison.mosaiccommerce.io`
   - Enable "Enforce HTTPS"

### Alternative: Subdirectory Setup

If you prefer `https://mosaiccommerce.io/tg-sitesearch-comparison`:

1. **Add this content** to your existing `mosaiccommerce.io` repository
2. **Place files** in a `tg-sitesearch-comparison/` subdirectory
3. **Configure redirects** in your main site to point to the subdirectory

## 📁 Project Structure

```
tg-sitesearch-comparison/
├── index.html          # Main webpage
├── README.md           # This file
├── CNAME              # Custom domain configuration
└── .github/
    └── workflows/
        └── deploy.yml  # GitHub Actions deployment (optional)
```

## 🛠️ Development

### Local Development

1. Clone the repository
2. Open `index.html` in your browser
3. Make changes and refresh to see updates

### Adding Features

- **Search Comparison Logic**: Add JavaScript for search functionality
- **Analytics Integration**: Connect to your preferred analytics platform
- **API Endpoints**: Configure search API endpoints
- **Styling**: Modify CSS in the `<style>` section of `index.html`

## 📊 Features

- 🔍 **Search Analysis**: Compare search algorithms and relevance
- 📊 **Performance Metrics**: Analyze speed and response times
- 🎯 **Relevance Testing**: Test search result quality
- 📈 **Analytics Dashboard**: Visualize performance data
- ⚡ **Real-time Comparison**: Side-by-side search testing
- 🔧 **Custom Configuration**: Flexible parameter testing

## 🔧 Configuration

### Search Endpoints

Configure your search endpoints by modifying the JavaScript section in `index.html`:

```javascript
const searchEndpoints = {
    'Platform A': 'https://api.platform-a.com/search',
    'Platform B': 'https://api.platform-b.com/search',
    // Add more endpoints as needed
};
```

### Custom Styling

Modify the CSS in the `<style>` section to match your brand:

```css
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
    --text-color: #333;
}
```

## 🚀 Deployment

### Automatic Deployment

The included GitHub Actions workflow automatically deploys changes when you push to the main branch.

### Manual Deployment

1. Make your changes
2. Commit and push to main branch
3. GitHub Pages will automatically rebuild and deploy

## 📝 License

This project is part of the Mosaic Commerce ecosystem.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📞 Support

For questions or support, please contact the Mosaic Commerce team.
