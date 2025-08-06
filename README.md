# Alec's Personal Website

The source code for my [personal website](https://alecdorrington.com/).

## Writing a New Post

1. Create a new file in [_posts](_posts/).
2. Name it according to `YYYY-MM-DD-title-of-post.md`.
3. Add the following preamble:
   ```yaml
   ---
   layout: post
   title: "Title of Post"
   date: YYYY-MM-DD HH:MM:SS -0000
   categories: category1 category2
   author: Your Name
   excerpt: "A brief description"
   ---
   ```
4. Write the content in [Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).
5. Commit and push.

## Local Execution

1. Install [Ruby](https://www.ruby-lang.org/en/).
2. Clone the repository `git clone https://github.com/SgtSwagrid/SgtSwagrid.github.io`.
3. Navigate to directory `SgtSwagrid.github.io/`
4. (Windows Only) Run `setup` (first time) then `run`.
5. Open [localhost:4000](http://localhost:4000/) in your browser.

## Deployment

This site is automatically deployed from the `main` branch.

## Tools

- [Jekyll](https://jekyllrb.com/) for static site generation.
- [GitHub Pages](https://pages.github.com/) for hosting.