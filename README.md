I'm not 100% sure this is a grunt-noflo-browser issue, but the graph runs just fine in flowhub and prints 'bang' to the console.

## steps to reproduce:

1. run `npm install` then `grunt`.
2. serve dist/main.html and open it in a browser.

here's a screenshot of the graph in flowhub: ![](http://f.monks.co/Screen-Shot-2015-09-18-at-11.52.44-PM-FFQ/Screen-Shot-2015-09-18-at-11.52.44-PM.png)

here's the text of the error in the chrome javascript console: 
```
Uncaught Error: No process defined for outbound node core/Repeat_ebeek
```
