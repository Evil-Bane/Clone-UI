

This repository contains a locally mirrored version of the Avrix preview site that was originally captured using HTTrack Website Copier. We have modified the mirrored code to clean up extraneous sections, simplify the structure, and ensure the website runs correctly in a local environment.

## Project Structure

- **index.html**  
  The landing page that displays a simple list of locally available sites. It links directly to the Avrix preview page.

- **50891774.html**  
  The modified preview page for the Avrix template. Unneeded sections have been removed, and necessary modifications (such as adding a jQuery reference) have been made to ensure proper functionality.

- **README.md**  
  This file, which explains the process and structure of the project.

## How the Website Was Made

1. **Mirroring the Original Site:**  
   The website was originally mirrored using [HTTrack Website Copier](https://www.httrack.com/). This tool downloaded the complete site including all assets and code.

2. **Cleaning Up the Code:**  
   - The **index.html** was simplified to only include the essential structure and a list of available sites.
   - The **50891774.html** file was trimmed by removing extra sections and unnecessary code that was not needed for the preview.  
   - Auto‑redirect meta tags and extraneous comments were removed to keep the code clean and maintain a more "human-coded" appearance.

3. **Ensuring Functionality:**  
   - A reference to the jQuery library was added in the preview file to support JavaScript functions.
   - The modified code now loads correctly both locally and on a server, displaying only the essential content.

## How to Run Locally

1. **Clone the Repository:**  
   Use Git to clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
