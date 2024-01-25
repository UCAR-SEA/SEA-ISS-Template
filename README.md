![SEA 2024 Logo](assets/logo_3.png)

># SEA ISS 2024 Notebook Submission Template 📓
[![JupyterBook](https://github.com/UCAR-SEA/SEA-ISS-Template/actions/workflows/gh-page_builder.yml/badge.svg)](https://github.com/UCAR-SEA/SEA-ISS-Template/actions/workflows/gh-page_builder.yml)
[![DOI](https://zenodo.org/badge/739166874.svg)](https://zenodo.org/doi/10.5281/zenodo.10499040)

This repository contains a template for submitting your paper to the [2024 Software Engineering Assembly Conference](https://sea.ucar.edu/event/sea-2024).

Please see the [how to use this template](#submission-guidelines.md) page for instructions on how to use this template.

## How to Use This Template 🛠️
**Estimated submission time: 30 minutes**

### Create your Paper Repository

1. **Create a New Repository Using this Template**: Click on the "Use this template" button to create a new repository with the files from this template. 
![Use this template](assets/use-this-template.png)

2. **Environment Setup**: Update the `requirements..txt` file and add any additional packages you may require. 

3. **Paper Information**: Fill in the details of your paper in this `README.md`, including the title, authors, abstract, and other relevant acknowledgements.

4. **Add your Paper**: Add your paper as a Jupyter Notebook in the `notebooks` folder. You can use multiple notebooks or one notebook if you wish. You can also use markdown files if you prefer.

```
notebooks/
|── introduction.md
├── notebook1.ipynb
└── notebook2.ipynb
```
5. **Update the Table of Contents**: Update the `toc.yml` file to include the notebooks you've added.
 
6. **Remove Instructions**: Once you've set up your repository, delete these instructions. 

7. **Commit your changes**: Commit and push your changes to your repository.

8. **Check your Jupyter Book**: Once you've pushed your changes, check that your Jupyter Book is building correctly. You can check the status of your Jupyter Book by clicking on the "Actions" tab of your repository.

### Ready to Submit your Paper? 📝

9. **Submit your Paper** : Once you've completed the steps above, you can submit your paper to the conference organizers:
* Once you are ready to submit your paper, go to the "Issues" tab of this repository and [click "New Issue"](https://github.com/UCAR-SEA/SEA-ISS-Template/issues/new).
* Someone from the SEA committee will add your github username to the list of collaborators for the UCAR-SEA github organization.
* Once you accepted the invitation, you can transfer your repository to the UCAR-SEA organization.
* Navigate to the settings of your paper repository, scroll down to the Danger Zone, and click "Transfer" . 
* Select or type "UCAR-SEA" to transfer the repository to the conference organizers. This step will make your paper public and allow the conference organizers to review your paper.

You can submit your paper as one notebook or split it up to multiple notebooks and markdown files. Please see the [example paper1](notebooks/notebook-template) and [example paper2](notebooks/notebook-example2_part1) for examples of how to structure your paper.

For your submissions, please use the following naming convention for your paper repository: `SEA-ISS-2024-<paper-title>`. For example, if your paper title is "My Awesome Paper", your repository name should be `SEA-ISS-2024-My-Awesome-Paper`.

For your submissions, please remove everything above this line and fill in the details of your paper here:

-----------------
![SEA 2024 Logo](assets/logo_3.png)
 
# Paper Title [Add Your Title Here]
[![JupyterBook](https://github.com/UCAR-SEA/SEA-ISS-Template/actions/workflows/gh-page_builder.yml/badge.svg)](https://github.com/UCAR-SEA/SEA-ISS-Template/actions/workflows/gh-page_builder.yml)
[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-green?style=flat-square&logo=Jupyter&color=green)](https://jupyter.org/try)
![Static Badge](https://img.shields.io/badge/DOI-10.XXXXX%2Fnnnnn-blue)

**Authors**: [List of Authors]

**Abstract**: [Your Abstract Here]

**Contributors**: [List any Contributors]

**Acknowledgements**: [List any Acknowledgements]

**License**: [Applicable License]

---

*Note: Replace the placeholders above with the specific details of your paper.*
  

