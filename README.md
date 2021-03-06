# camt.li

The [camt.li](http://camt.li) web site provides simple higher level
inspection of camt.05x files, as provided by PostFinance in Switzerland.

Specifically, the script recognizes:

- `camt.053.001 V4`
- `camt.054.001 V4`

Analysis is done by picking items in the XML without doing any real
file parsing. No data leaves the browser and all the processing is
done on the client.

More information about the project can be found on [this blog post](http://code.fitness/post/2016/05/camt-website.html).

## About the current design

The graphic design of the site was done by Gilles Gfeller and the initial analysis
logic by Pierre Arnaud (this is an example of _duct tape programming_). Jonny Quarta
currently maintains this code base.

The background picture was shot above Preda (GR) in Switzerland.

## Deployment

```sh
npm install
npm run compile
upload-ftp.bat
```
