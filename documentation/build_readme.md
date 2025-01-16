This has been built using [Jupyter Book](https://jupyterbook.org/) and [GitHub Pages](https://pages.github.com/). Jupyter Books are written using the MyST markdown extensions. Useful guidance on the syntax can be found at this [cheat sheet](https://jupyterbook.org/en/stable/reference/cheatsheet.html)

To build this book, run the following command from the directory containing this folder:

> jupyter-book build documentation

> [!NOTE]
> For the first build, run `jupyter-book clean documentation` to remove any images or files from previous builds no longer used (particularly important if copying from an old workshop).

This will create a folder called `_build` containing the built book. You can open the book by opening the file `/documentation/_build/html/index.html` in a web browser.

Copy all the files from `/documentation/_build/html` to the `docs` folder where GitHub Pages will serve it from. 

```{warning}
GitHub requires a `.nojekyll` file to be present in the `docs` folder to prevent it from ignoring the formatting of the built book.
```
