# drthesmos.github.io

A personal website based on the Jekyll-Emerald theme.

## Key Features & Benefits

*   **Clean and Minimalist Design:** Leverages the Emerald theme for a visually appealing and uncluttered user experience.
*   **Jekyll-Powered:**  Benefits from Jekyll's static site generation, ensuring fast loading times and easy deployment.
*   **Customizable:** Offers various configuration options and includes for easy personalization of the theme.
*   **Mobile-Responsive:**  Designed to be responsive and accessible across different devices.
*   **GitHub Pages Ready:**  Intended for seamless deployment to GitHub Pages.

## Prerequisites & Dependencies

*   **Jekyll:**  Required to build and serve the site locally. Installation instructions can be found at [https://jekyllrb.com/docs/installation/](https://jekyllrb.com/docs/installation/)
*   **Ruby:** Jekyll is a Ruby gem, so Ruby must be installed on your system.
*   **Bundler:** A dependency management tool for Ruby. Install with `gem install bundler`.

## Installation & Setup Instructions

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/luxowner/luxowner.github.io.git
    cd luxowner.github.io
    ```

2.  **Install dependencies:**

    ```bash
    bundle install
    ```

3.  **Build and serve the site locally:**

    ```bash
    bundle exec jekyll serve
    ```

4.  **Access the site:**  Open your web browser and navigate to `http://localhost:4000`.

## Usage Examples & API Documentation (if applicable)

This project is a static site; there is no API. To customize the content, edit the Markdown files in the root directory and the HTML files in the `_includes` and `_layouts` directories.

*   **Adding a new page:** Create a new `.md` file in the root directory with YAML front matter:

    ```md
    ---
    layout: page
    title: About Me
    ---

    This is the content of the about me page.
    ```

*   **Editing the navigation:** Modify the `_includes/menu.html` file to adjust the navigation links.

## Configuration Options

The main configuration file is `_config.yml`.  Here are some key configurable settings:

*   **`title`:**  The title of your website.
*   **`description`:**  A short description of your website.
*   **`baseurl`:**  The subpath of your site if it is hosted in a subdirectory (e.g., `/blog`).  Leave blank if hosting at the root domain.
*   **`url`:** The base URL of your site.
*   **`author`:**  Your name.

Example `_config.yml`:

```yaml
title: My Awesome Website
description: A personal website built with Jekyll and the Emerald theme.
baseurl: "" # No subpath
url: "https://example.com"
author: John Doe
```

## Contributing Guidelines

Contributions are welcome! Here's how you can contribute:

1.  **Fork the repository.**
2.  **Create a new branch for your feature or bug fix:**

    ```bash
    git checkout -b feature/your-feature-name
    ```

3.  **Make your changes and commit them with descriptive messages.**
4.  **Push your changes to your fork:**

    ```bash
    git push origin feature/your-feature-name
    ```

5.  **Create a pull request to the `main` branch of the original repository.**

## License Information

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

*   This project is based on the [Jekyll-Emerald Theme](https://github.com/digitalnature/jekyll-emerald).  Thanks to the original author for creating this beautiful theme.
