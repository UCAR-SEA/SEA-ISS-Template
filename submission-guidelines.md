# How to Use This Template 🛠️

**Estimated submission time: 30 minutes ⏰**

**This page includes the submission guidelines of SEA 2025 conference.**

## Create your Paper Repository

1. **Create a New Repository Using this Template**: Click on the "Use this template" button to create a new repository with the files from this template. 
![Use this template](assets/use-this-template.png)

```{note}
   If you want to learn more about Git and GitHub, you can check out the following tutorials: 
   - [Version Control with Git](https://swcarpentry.github.io/git-novice/)
   - [Git Branching Guide](https://learngitbranching.js.org/)
```

2. **Name your Repository**: Name your repository using the following naming convention: `SEA-ISS-2025-<paper-title>`. For example, if your paper title is "My Awesome Paper", your repository name should be `SEA-ISS-2025-My-Awesome-Paper`.


3. **Activate GitHub Pages**: Once you created your repository, go to the settings of your repository, scroll down to the "Pages" section, and under "Build and deployment" choose Source: "GitHub Actions". This will allow you to view your Jupyter Book online.
This will be automatically triggered when you push your changes to your repository. Once you activate this, you can view your Jupyter Book by clicking on the link provided in the "Pages" section of your repository settings. If you have any issues with this step, please reach out to the [conference organizers](mailto:iss_proceedings@ucar.edu).

4. **Environment Setup**: Update the `environment.yml` file and add any additional packages you may require. 

5. **Paper Information**: Fill in the details of your paper in this `README.md`, including the title, authors, abstract, and other relevant acknowledgements. At this step, don't worry about the DOI badge, you will update this later.

6. **Add your Paper**: Add your paper as Jupyter Notebooks or markdown files under the `notebooks` folder. You can use one notebook or multiple notebooks if you wish. You can also use markdown files if you prefer.

    ```
    notebooks/
    |── introduction.md
    ├── notebook1.ipynb
    └── notebook2.ipynb
    ```

    This framework supports [the MyST Markdown language](https://jupyterbook.org/en/stable/reference/glossary.html#term-MyST) in Markdown and notebook documents. This allows users to write rich, publication-quality markup in their documents.

    [Example paper 1](notebooks/notebook-template) and [Example paper 2](notebooks/example_2/notebook-example2_part1) are provided to help you get started.
    You can either organize all your content in 1 notebook (or markdown file) similar to [this example](notebooks/notebook-template.ipynb) or split it up into multiple notebooks (or markdown files) similar to the [example 2](notebooks/example_2/notebook-example2_part1.md).


7. **Update the Table of Contents**: Update the `_toc.yml` file to include the notebooks you've added. Remove the extra examples from the `_toc.yml` file.

8. **Commit your changes**: Commit and push your changes to your repository.

9.  **Check your Jupyter Book**: Once you've pushed your changes, check that your Jupyter Book is building correctly. You can check the status of your Jupyter Book by clicking on the "Actions" tab of your repository.


```{tip}
**Citations and Bibliography**: For adding citations to your paper and referencing others, please see our detailed guidelines [here](notebooks/example_2/notebook-example2_references.md). In short, after adding your references to your `references.bib` file, you can add the citation to your paper using the `{cite}[authoryearkey]` syntax.
```

``` {hint}
If you are more comfortable using word or latex, you can convert your document to markdown using [pandoc](https://pandoc.org/). To learn more about how to convert your word document to markdown, you can check out [this tutorial](https://bcrf.biochem.wisc.edu/2022/12/30/learn-markdown-episode-6-convert-word-to-markdown-with-pandoc/).
```

If you have any questions or need help with your submission, please reach out to the [conference organizers](mailto:iss_proceedings@ucar.edu) or open an issue in this repository.

## Ready to Submit your Paper? 📝

* **Submit your Paper:** Once you've completed the steps above, you can submit your paper to the [conference organizers](mailto:iss_proceedings@ucar.edu):
  * Once you are ready to submit your paper, go to the "Issues" tab of this repository and [click "New Issue"](https://github.com/UCAR-SEA/SEA-ISS-Template/issues/new).
  * Someone from the SEA committee will add your github username to the list of collaborators for the UCAR-SEA github organization.
  * Once you accepted the invitation, you can transfer your repository to the UCAR-SEA organization.
  * Navigate to the settings of your paper repository, scroll down to the Danger Zone, and click "Transfer" . 
  * Select or type "UCAR-SEA" to transfer the repository to the [conference organizers](mailto:iss_proceedings@ucar.edu). This step will make your paper public and allow the [conference organizers](mailto:iss_proceedings@ucar.edu) to review your paper.


### Make Zenodo DOI for your paper

12. **Make Zenodo DOI for your paper:** Once you've completed the steps above, you can make Zenodo DOI for your paper:

    * Go to [Zenodo](https://zenodo.org/) and login with your GitHub account.
    * Click on "New Upload" and select your paper repository.
    * You need to first create a new release for your paper repository. Click on "Create a new release" and add the version number of your paper. For example, if this is the first version of your paper, you can add "v1.0.0" as the version number.
    * Once you've created a new release, you can go back to the "New Upload" page and select the version of your paper and create a new DOI for your paper.


13. **Update the DOI badge**: Once you've created a new DOI for your paper, you can update the DOI badge in the README.md file of your paper repository with the new DOI.

## Configure Binder for your paper:

**Update or remove the Binder badge**
    
* For those who would like their papers to be easily launched in an executable environment based upon the specifications in the repository, you can update the Binder badge in the README.md to appropriately reflect your repository name and path to your notebooks.  You can find more information about how this works on the [My Binder website](https://mybinder.org/).
* If your notebooks are not interative or you would rather not include this feature, simply remove the line for the Binder badge in the README.md file. 


-----------------

```{tip}
You can submit your paper as one notebook or split it up to multiple notebooks and markdown files. Please see the [example paper1](notebooks/notebook-template) and [example paper2](notebooks/example_2/notebook-example2_part1) for examples of how to structure your paper.
```

```{note}
Please reach out to the [conference organizers](mailto:iss_proceedings@ucar.edu) or open an issue or a discussion in this repository if you have any questions or need help with your submission.
```
