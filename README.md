## gobyexample

Source for the [Go by Example](https://gobyexample.com)
documentation project.


### Generation

The web site is generated from `.go` and `.md` source
files using a custom site generator.

Generation requires the [`pygmentize`](http://pygments.org/)
binary for syntax highlighting.

To validate the source, generate the site, and open the
home page in your browser:

```console
$ tool/build
$ open site/index.html
```

### License

This work is licensed under a [Creative Commons Attribution 3.0 Unported License](http://creativecommons.org/licenses/by/3.0/).
