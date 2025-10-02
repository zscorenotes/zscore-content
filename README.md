# ZSCORE.studio Content Repository

This repository contains all content data for ZSCORE.studio website, including articles, portfolio items, services, and images.

## Structure

```
├── content/
│   ├── services/     # HTML content files for services
│   ├── portfolio/    # HTML content files for portfolio items
│   └── news/         # HTML content files for news articles
├── images/           # All images used across the website
├── news.json         # News articles metadata
├── services.json     # Services metadata
├── portfolio.json    # Portfolio items metadata
├── about.json        # About page content
├── settings.json     # Site settings and configuration
└── categories.json   # Category definitions

```

## Content Management

This repository is automatically managed by the ZSCORE.studio admin panel. Content editors can:

- Create, edit, and delete content through the web interface
- Upload and manage images
- Configure site settings and categories
- Organize content with tags and categories

## API Access

The main website fetches content from this repository using GitHub's API. Content is cached and optimized for performance.

## Contributing

This repository is public to allow for community contributions and transparency. However, content changes should primarily be made through the admin panel to maintain consistency and data integrity.

## License

Content in this repository is proprietary to ZSCORE.studio. Images and written content are protected by copyright.