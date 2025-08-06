# SgtSwagrid's Blog

A Jekyll-powered blog hosted on GitHub Pages.

## Setup for Local Development

1. **Install Ruby and Jekyll**
   ```bash
   gem install jekyll bundler
   ```

2. **Clone this repository**
   ```bash
   git clone https://github.com/SgtSwagrid/SgtSwagrid.github.io.git
   cd SgtSwagrid.github.io
   ```

3. **Install dependencies**
   ```bash
   bundle install
   ```

4. **Serve the site locally**
   ```bash
   bundle exec jekyll serve
   ```

5. **Open your browser**
   Navigate to `http://localhost:4000`

## Adding New Posts

1. Create a new file in the `_posts` directory
2. Name it using the format: `YYYY-MM-DD-title-of-post.md`
3. Add the required front matter:
   ```yaml
   ---
   layout: post
   title: "Your Post Title"
   date: YYYY-MM-DD HH:MM:SS -0000
   categories: category1 category2
   author: SgtSwagrid
   excerpt: "A brief description of your post"
   ---
   ```
4. Write your content in Markdown below the front matter
5. Commit and push to GitHub - the site will automatically update!

## Customization

- **Site settings**: Edit `_config.yml`
- **Styling**: Modify the CSS in `_layouts/default.html`
- **Navigation**: Update the nav section in `_layouts/default.html`
- **About page**: Edit `about.html`

## Deployment

This site is automatically deployed to GitHub Pages when you push to the `main` branch. No additional setup required!

## Built With

- [Jekyll](https://jekyllrb.com/) - Static site generator
- [GitHub Pages](https://pages.github.com/) - Hosting platform
- Custom CSS for styling
