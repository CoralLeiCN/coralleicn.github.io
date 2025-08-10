# Gemini Guidelines for `coralleicn.github.io`

This document provides guidelines for interacting with the `coralleicn.github.io` project.

## About this project

This is a personal blog website built with [Hugo](https://gohugo.io/) and the [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme. The website is hosted on GitHub Pages.

## Getting started

### Prerequisites

Before you begin, ensure you have the following installed:

*   [Hugo](https://gohugo.io/getting-started/installing/) (extended version)
*   [Go](https://go.dev/doc/install)

### Installation

1.  Clone the repository:

    ```bash
    git clone https://github.com/CoralLeiCN/coralleicn.github.io.git
    ```

2.  Navigate to the project directory:

    ```bash
    cd coralleicn.github.io
    ```

3.  Initialize the Hugo modules:

    ```bash
    hugo mod init github.com/CoralLeiCN/coralleicn.github.io
    ```

## Development

### Running the development server

To start the local development server, run the following command:

```bash
hugo server
```

This will start a local server, usually at `http://localhost:1313/`. The site will automatically reload when you make changes to the content or source files.

### Creating new content

To create a new post, use the `hugo new` command:

```bash
hugo new content/posts/my-new-post.md
```

This will create a new Markdown file in the `content/posts` directory with the appropriate front matter.

## Building and deployment

### Building the site for production

To build the static site, run the following command:

```bash
hugo
```

This will generate the static files in the `public` directory.

### Deployment

This site is automatically deployed to GitHub Pages when changes are pushed to the `main` branch.
