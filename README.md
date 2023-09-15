## About this document 

This is a collection of notes and commented code that serves--or at least tries to serve--as an overview of the work I've done with TASCHA over the past year. This means there are several genres of topic being covered:

- *data*, as in information about the nature of the PLS (Public Library Survey) and E-Rate data;
- *tooling*, as in findings and suggestions for script-level changes and upgrades to the existing scripts;
- *scripting*, as in features/code I have written and why;
- *architecture*, plans for long-term development and explanations of why they're like that from my perspective 

It is written in a conversational style because that was more conducive to getting more information down in place as opposed to less information. Thanks in advance for bearing with me on that front.

---

## About the template this repository uses:

This is a minimal bookdown example. Although you see a few files here, only `index.Rmd` is required. All other files are optional, but `bookdown-minimal.Rproj` can make it much easier to build the book.

The key is the `site` setting in `index.Rmd`. If you want to build the book in RStudio, just click the `Build Book` button in the `Build` pane, otherwise call the function in R:

```r
bookdown::render_book('index.Rmd', 'all')
```
