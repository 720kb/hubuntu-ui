# Hubuntu UI

<br>

![Ubuntu-material-dashboard-admin](http://i.imgur.com/HtL6qUq.png)

Hubuntu UI is a Material _Ubuntu style_ , very basic , starter template for admin dashboards (materialize.css).

The Hubuntu UI is developed by [720kb](http://720kb.net).

### Requirements
 
You need [Bower](http://bower.io/) installed on your pc.

### Install

```bash
git clone git@github.com:720kb/hubuntu-ui.git hubuntu-ui
```

```bash
cd hubuntu-ui/
```

```bash
bower install
```
#### npm

```bash
npm install hubuntu-ui
```
#### Bower
```bash
bower install hubuntu-ui
```

### Run it
```bash
python -m SimpleHTTPServer
```
then go to http://localhost:8000

****With Gulp****
```bash
npm install && gulp serve
```
then go to http://localhost:8100

### Live demo

[https://720kb.github.io/hubuntu-ui/](https://720kb.github.io/hubuntu-ui/)

### Sass
A Sass version of Hubuntu UI is included for convenience.  
To generate a compiled css version simply run:
 
```bash
sass sass/hubuntu.scss:css/main.css
```
To test the compiled Sass version remove all the style tags in the sample index.html and replace them with:

```
<link href="css/main.css" type="text/css" rel="stylesheet" media="screen, projection">
```

### Theming
For any changes to the theme please look at the materialize.css [documentation](http://materializecss.com/).

### Contributing

We will be much grateful if you help us making this project to grow up.
Feel free to contribute by forking, opening issues, pull requests etc.

### License

The MIT License (MIT)

Copyright (c) 2015 Filippo Oretti

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
