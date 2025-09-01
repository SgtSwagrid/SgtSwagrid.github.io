# alecdorrington.com

The source code for my [personal website](https://alecdorrington.com/).

## Local Execution

1. Install [Ruby](https://www.ruby-lang.org/en/), [Bundler](https://bundler.io/), and [Git](https://git-scm.com/).
2. Clone the repository:
   ```bash
   git clone https://github.com/SgtSwagrid/SgtSwagrid.github.io
   ```
4. From the project directory, run `setup` (first time) then `run`.
5. Open [localhost:4000](http://localhost:4000/) in your browser.

## Writing a New Post

1. Create a new file in [_posts](_posts/).
2. Name it according to `YYYY-MM-DD-title-of-post.md`.
3. Add the following preamble:
   ```yaml
   ---
   layout: post
   title: "Title"
   date: YYYY-MM-DD HH:MM:SS -0000
   author: Author's name
   excerpt: "A brief description"
   ---
   ```
4. Write the content in [Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax), with optional [LaTeX](https://www.latex-project.org/) equations.
5. Commit and push.

## Deployment

This site is automatically deployed from the `main` branch.

## Tools

- [Jekyll](https://jekyllrb.com/) for static site generation.
- [GitHub Pages](https://pages.github.com/) for hosting.
- [MathJax](https://www.mathjax.org/) for in-browser LaTeX-style equations.