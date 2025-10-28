# jorgedlt.github.io

This is the source code for my personal blog, "BASHista Worker's Paradise", hosted on GitHub Pages using Jekyll.

## About

A blog dedicated to Bash scripting, exploring advanced uses of Bash for tasks typically not done in scripting languages, like image and binary transformations. It's fun, challenging, and minimalist.

## Site Access

The live site is available at: https://jorgedlt.github.io

## Local Development

To run the site locally for development or testing:

1. **Prerequisites**: Install Ruby, Jekyll, and Bundler
   ```bash
   gem install jekyll bundler
   ```

2. **Clone the repository**:
   ```bash
   git clone https://github.com/jorgedlt/jorgedlt.github.io.git
   cd jorgedlt.github.io
   ```

3. **Install dependencies**:
   ```bash
   bundle install
   ```

4. **Serve the site locally**:
   ```bash
   bundle exec jekyll serve
   ```
   The site will be available at `http://localhost:4000`

5. **Build for production** (optional):
   ```bash
   bundle exec jekyll build
   ```

## Writing Posts

Posts are written in Markdown and stored in the `_posts` directory (currently using `jekyll/update/` structure). Use Jekyll's front matter for metadata.

## Deployment

The site automatically deploys to GitHub Pages on pushes to the main branch.

## Contact

- Email: jorgedlt@gmail.com
- GitHub: [@jorgedlt](https://github.com/jorgedlt)
- Twitter: [@jorgedlt](https://twitter.com/jorgedlt)

## RSS Feed

Subscribe via RSS at: https://jorgedlt.github.io/feed.xml
