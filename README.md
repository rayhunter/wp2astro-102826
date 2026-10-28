# wp2astro-102826

A WordPress site migrated to Astro with Decap CMS integration.

## 🚀 Quick Start

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build
```

## 📝 Content Management

Visit `/admin/` to access the Decap CMS interface for content management.

## 🔧 Development

This site was migrated from WordPress using an automated migration tool that:

- Extracted all WordPress content via REST API
- Converted HTML to Markdown with proper frontmatter
- Generated Astro project structure with content collections
- Set up Decap CMS for ongoing content management
- Configured GitHub integration for version control

## 📁 Project Structure

```
wp2astro-102826/
├── src/
│   ├── content/
│   │   ├── blog/          # Blog posts
│   │   └── pages/         # Static pages
│   ├── layouts/           # Astro layouts
│   └── pages/             # Route pages
├── public/
│   ├── admin/             # Decap CMS
│   └── uploads/           # Media files
└── package.json
```

## 🎨 Customization

- Edit layouts in `src/layouts/`
- Modify styles in the layout files
- Add new content types in `public/admin/config.yml`
- Customize the CMS interface as needed

Built with ❤️ using Astro and Decap CMS.
