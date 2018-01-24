### This is a presentation about the paper 'Differentiable Learning of logical rules for knowledge base reasoning' by Yang, Yang and Cohen 
by me, for WS1718 @ unibonn

It started as iypnb notebook and evolved into and ipynb-reveal-presentation. Finally I had to write my own template to include local cdns into the converted html file, for using the presentation offline.

## Usage

Command for transforming the notebook into a html

```bash
    jupyter nbconvert ownNLP.ipynb --to slides --template=offline.tpl
```

### Dependecies

You need a local copy of 
* [reveal.js](https://github.com/hakimel/reveal.js/) in a folder *reveal.js*
* cdn of [font-awesome](https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.1.0/css/font-awesome.css) copied into /CDNs/ and renamed to *font-awesome-cdn.css*
* cdn of [require.js](https://cdnjs.cloudflare.com/ajax/libs/require.js/2.1.10/require.min.js) copied into /CDNs/ and renamed *require.min.js*
* cdn of [jquery.js](https://cdnjs.cloudflare.com/ajax/libs/jquery/2.0.3/jquery.min.js) copied into /CDNs/ and renamed to *jquery.min.js*
* cdn of [MathJX](https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.2/MathJax.js?config=TeX-MML-AM_CHTML) copied into /CDNs/ and renamed to *mathjax.js*
* and for your convenience a custom.css in the folder where the .ipynb lies. 

export the command builds a presentation with reveal.js which loads local and/or cdns of the dependencies.

