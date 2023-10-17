## Elijah Résumé

## Introduction
This was a fork from Thomas Highbaugh's resume template.

## How to run it
Clone the git repository 
```
git clone https://github.com/Thomashighbaugh/resume
```

Navigate to the base directory:

```
cd resume
```

Install the dependencies:

```
yarn install
```

Start the development server after building the stylesheet out of the Tailwind configuration:

```
yarn build && yarn serve
```

Only generate CSS that is used on the page which results in a much smaller file size:

```
yarn build
```

<hr>

## Starting Point

`docs/index.html` is the main content file. By copying HTML: add pages, sections, subsection, and other parts.

`npm run build` enables drag and drop support of the `docs` directory, which you find helpful unloading your copy on GitHub if terminal/command prompt is not your thing. 

<hr>

## Tailwind CSS

A nice bootstrap alternative that doesn't have as much opinionation that is all the rage these days with the 'hates css' crowd that while not a part of, I definitely didn't want to fall behind and thus I took this oppurtunity to practice a bit. 

**Note:** The way I am using Tailwind here varies wildly from the way I use it elsewhere and is a bit of an old school way to deploy it but `it works` just fine so I am not going to throw the monkey wrench in the project anytime soon on that front. 

<hr>


## Custom CSS

Code from `tailwind.config.js` and `tailwind.css` transpiles to `docs/style.css`.

<hr/>

## Balanced Columns

Removing `col-fill-auto` class will make both columns equally tall. Moreover, removing `md:h-letter` and `md:h-letter-col` classes will eliminate fixed proportions of the letter or A4 page — thereby removing unnecessary vertical space when displaying short columns.

<hr/>


## Printing

### Chrome

Right-click → Print.  

OR 

You can save it as a PDF which will probably keep the SVG image and the other things being stripped out by the print optimizations, but there are use cases for that as well and its not like there really is a `right way` 

------

### Firefox

File → Print.

### Adobe Acrobat Reader

File → Print.

By clicking on the **Page Setup** button, you are taken to the window with A4 and Letter options.



