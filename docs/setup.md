# Setup and Installation of GitHon

Getting GitHon installed and ready-to-go should only take a few minutes.

### Local Installation

##### Requirements

Installing GitHon is easy and straightforward. Your system just needs to meet these two requirements:

* NodeJS (v10.0.0 and above is recommended)
* Windows, Linux, Unix, or Mac OS X

##### Install with NPM

The best way to install GitHon is via **NPM** or **Yarn** At the terminal prompt, simply run the following command to install GitHon:

```
$ npm install githon --save-dev
# or
$ yarn install githon --save
```

##### Create a book

GitHon can setup a boilerplate book:

```
$ githon init
```

If you wish to create the book into a new directory, you can do so by running `githon init ./directory`

Preview and serve your book using:

```
$ githon serve
```

Or build the static website using:

```
$ githon build
```


##### Debugging

You can use the options `--log=debug` and `--debug` to get better error messages (with stack trace). For example:

```
$ githon build ./ --log=debug --debug
```

