# Data Sharing

## Creating slides from markdown using `reveal.js`

Based on [Bérénice's slides](https://github.com/bebatut-slides/backofen_lab_retreat_04_17) and [Mark's ones](https://github.com/datachampcam/data-formatting).

### Add `reveal.js` as a submodule

```bash
cat .gitmodules
[submodule "reveal.js"]
	path = reveal.js
	url = https://github.com/hakimel/reveal.js.git

git submodule add https://github.com/hakimel/reveal.js.git reveal.js
```

### Add `css/custom.css` and `index.html` files

### Add `slides.md`

Push the file to GitHub and turn on GitHub Pages on master branch.
Go to url https://datachampcam.github.io/data-sharing/slides.html
