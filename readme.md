# Jekyll + ZURB Template

This is a Jekyllized version of the [official ZURB Template](https://github.com/zurb/foundation-zurb-template) for use with [Foundation for Sites](http://foundation.zurb.com/sites). Zurb's [Panini](https://github.com/zurb/panini) and [Style Sherpa](https://github.com/zurb/style-sherpa/) have been removed and [Jekyll](http://jekyllrb.com/) has been added. Everything else has remained pretty much the same.

## Installation

```
git clone https://github.com/huphtur/jekyll-foundation-zurb-template projectname
```

Then open the folder in your command line, and install the needed dependencies:

```
cd projectname
npm install
bower install
```

Finally, run `npm start` to run Gulp. Your finished site will be created in a folder called `dist`, viewable at this URL:

```
http://localhost:8000
```

To create compressed, production-ready assets, run `npm run build`.
