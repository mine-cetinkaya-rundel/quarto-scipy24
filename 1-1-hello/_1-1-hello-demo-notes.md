# 1-1-hello

`hello-penguins.qmd`

-   Run individual cells

-   Render the whole a document

-   Editing with source editor to make a word bold and render

-   Turn on visual editor and unbold the word, make another italic

-   Using the visual editor, 
	- insert the penguins illustration, 
	- add caption and alt-text, 
	- center align,
	- render, pop out the rendered document to browser, inspect to show alt text
	- In the yaml add `lightbox: true` under `date` and rerender to show what it does

-   Insert the followint table with the visual editor

	Island		Coordinates
	Biscoe 		65°26′S 65°30′W
	Dream		64°44′S 64°14′W
	Torgersen	64°46′S 64°5′W

	Render. Then change alignment of a column, and re-render

	Go back to the source editor to see the source code for all of this and show the git diff.

-   Customizing formats: `pdf`, `docx`, `revealjs`
	- Change format to `pdf` and re-render
	- Change format to `docx` and re-render
	- Change format to `revealjs` and re-render, scroll through and say you'll say more about this later

-   Customizing format options:  `code-fold`, `toc`
	- Add `code-fold: true` and re-render
	- Add `toc: true` and re-render

-   Code cells: labels, alt-text, execution options (`echo`, `warning`)
	- Labels are optional but good for jumping to area from top navigation in editor
	- Inspect the output for alternative text in figure
	- Add `warning: false` to code cell with figure and re-render
	- Add `execute > echo: false` to document YAML and re-render

-   Cross referencing figures and tables, with and without the visual editor
	- Replace text like figure/table below and re-render
	- Show hover preview

-   Converting between Jupyter Notebooks and plain text markdown documents
	- In the terminal, run `quarto convert hello-penguins.qmd`
	- Open the ipynb
	- Click on Run all, show the files generated, or say you can run chunk by chunk
	- Conversion can go both ways

