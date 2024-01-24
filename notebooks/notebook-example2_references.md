# References

You can add references to your paper by adding them to the `references.bib` file. You can then cite them in your paper using the `[@citekey]` syntax.

Please see the [Jupyter Book documentation](https://jupyterbook.org/en/stable/content/citations.html#basic-citations) for more information on how to add references to your paper.

To add a reference to your paper, you can use the following steps:

1. Add your reference to the `references.bib` file. You can use [Google Scholar](https://scholar.google.com/) to find the BibTeX entry for your reference. 

Here is an example: 
```
@article{perez2011python
,	title	= {Python: an ecosystem for scientific computing}
,	author	= {Perez, Fernando and Granger, Brian E and Hunter, John D}
,	journal	= {Computing in Science \\& Engineering}
,	volume	= {13}
,	number	= {2}
,	pages	= {13--21}
,	year	= {2011}
,	publisher	= {AIP Publishing}
}
```

2. Add the citation to your paper using the `[@citekey]` syntax. For example, to cite the paper above, you can use the following syntax: `[@perez2011python]`.

For example:
```
 Here is my nifty citation {cite}`perez2011python`.
```
Will result in :

Here is my nifty citation {cite}`perez2011python`.



3. Add references to the end of your paper. You can do this by adding the following code to the end of your paper:

````md
```{bibliography}
```
````

The above code will add the references, for example:
```{bibliography}
```


4. **Alternatively**, if you choose to have seperate sections for the different parts of the paper, update the `toc.yml` file to include the `references.bib` file. This will add the references to the end of your paper.
