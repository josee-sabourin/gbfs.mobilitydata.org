# gbfs.org

Source code for [gbfs.org](https://gbfs.org/). 

This site was built using [MkDocs](https://www.mkdocs.org/), a static site generator, and [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/), a technical documentation theme for MkDocs.

## Editing site

To edit the General Bikeshare Feed Specification reference, go to the [MobilityData/gbfs](https://github.com/MobilityData/gbfs/) repository.

To propose a feature, content addition, or UI/UX improvement, open an [issue](https://github.com/MobilityData/gbfs.org/issues/new) or [pull request](https://github.com/MobilityData/gbfs.org/pulls) on this repository. 

Alternatively, you can provide feedback using this [form](https://mobilitydata.typeform.com/to/BCiwESfg).

## Building the site locally

1. In Terminal, change the directory to one where you wish to build the site.
1. Ensure you have an up-to-date version of pip: 
   - Linux: `pip install pip` or `pip install --upgrade pip`
   - macOS: `pip3 install pip` or `pip3 install --upgrade pip`
1. Clone this repository:
   - `git clone https://github.com/MobilityData/gbfs.org`
1. Change the directory to the cloned repository, and have [`requirements.txt`](requirements.txt) installed:
   - Linux: `pip install --force-reinstall -r requirements.txt`
   - macOS: `pip3 install --force-reinstall -r requirements.txt`
1. Assuming you are still in the cloned repository, run this command to update the content for the specification references and best practices:
   - `bash scripts/fetchdata.sh`
1. To run the site locally: `mkdocs serve`
1. To build the site locally only: `mkdocs build --clean`
1. To deploy the site to GitHub Pages: `mkdocs gh-deploy`

## License

Except as otherwise noted, the content of this site is licensed under the [Creative Commons Attribution 3.0 License](https://creativecommons.org/licenses/by/3.0/).
