# VisionsTrust Documentation

This repo contains the source documentation files for a build using MKDocs.

## Building

To build the documentation, follow these steps:

1. Ensure you have `mkdocs` installed on your machine. If you don't have it installed, you can follow the official setup guide for `mkdocs` to install it.
2. Once `mkdocs` is installed, navigate to the root directory of this repository.
3. Run the command `mkdocs build` to generate the documentation.
4. After the build process is complete, you will find the generated documentation in the "site" directory.
5. You can now deploy the contents of the "site" directory to any web server or application.

For more information on how to use `mkdocs`, refer to the official documentation.

Feel free to explore the different sections of this repository to learn more about the documentation structure and how to contribute.

## Plugins
In order to build after updates, you need to have python and the following packages installed

### MKDocs
```bash
pip install mkdocs
```

### Mermaid Support
```bash
pip install mkdocs-mermaid2-plugin
```

### Theme
```bash
pip install mkdocs-material
```

### Auto revision file updates
```bash
pip install mkdocs-git-revision-date-localized-plugin
```

### Install using requirements.txt
You can also install everything at once by running
```bash
pip install -r requirements.txt
```