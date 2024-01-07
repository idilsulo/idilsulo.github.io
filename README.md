# Minima for Academics + Dark mode

## Personal Website
This is the source code to my personal website on https://idilsulo.github.io. 

Feel free to clone & adapt this repository for your own use.

### Important

Please make sure to **remove the analytics tags** as you would not want them on your own website. 

When using this repository for your own purposes, remove the following code segment from `head.html`:

```
  <!-- Google tag (gtag.js) -->
  <script async src="https://www.googletagmanager.com/gtag/js?id=G-E559NMEVTK"></script>
  <script>
    window.dataLayer = window.dataLayer || [];
    function gtag(){dataLayer.push(arguments);}
    gtag('js', new Date());

    gtag('config', 'G-E559NMEVTK');
  </script>
  <script>
      if (localStorage.getItem('color-theme') === 'darkmode' || (!('color-theme' in localStorage))) {
        localStorage.setItem('color-theme', 'darkmode');
      }
  </script>
```

## Setup

This site is built on top of [Jekyll Minima theme](https://github.com/jekyll/minima) with changes to display publications and dark mode support.

To test this theme on your local, run:
```
bundle exec jekyll serve
```

Then, open your browser at `http://localhost:4000`.