# Generator for Akana Community Manager Default Theme

> [Yeoman](http://yeoman.io) generator
> [npm: generator-akana-theme](https://www.npmjs.com/package/generator-akana-theme)

## Description:

This generator provides a set of starter customization files for customizing the Default Theme of Akana's Community Manager.

### Install

Use yeoman to search for and install the generator: `yo` and pick "Install a generator", then search for "akana," and choose "akana-theme".

or...

```
npm install -g generator-akana-theme
```
### Run

Use yeoman and pick `akana-theme`

or ...

```
yo akana-theme
```

You'll be prompted for a company name (ex. `Custom Starter`) and a directory named `CM_` plus the company name (ex.`CM_CustomStarter`) will be created with the following contents:


* `contents/`: a directory that contains a landing page customization, and can be uploaded to `contents/home/landing`
* `resources/`: a directory that contains resources (favicon, site title, images), and can be uploaded to `resources/theme/default`
* `custom.less`: a `custom.less` file ready for editing

# Development

See [Authoring Yeoman Generators](http://yeoman.io/authoring/index.html) as well as the [generator-generator](https://github.com/yeoman/generator-generator) for more info.

For local development usage, to allow `yo` to look locally rather than npm:

* clone this repo
* cd `generator-akana-theme`
* `npm link`

Now `yo` will look for the cloned repo, local copy, of the generator.
