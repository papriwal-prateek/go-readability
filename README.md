go-readability
==============

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/320d73fefbda44fda309013fdc1d30c6)](https://www.codacy.com/app/prateek-papriwal/go-readability?utm_source=github.com&utm_medium=referral&utm_content=papriwal-prateek/go-readability&utm_campaign=badger)

go-readability is library for extracting the main content off of an HTML page. This library implements the readability algorithm created by arc90 labs and was heavily inspired by https://github.com/cantino/ruby-readability.

Installation
------------

`go get github.com/mauidude/go-readability`

Example
-------

```
import(
  "github.com/mauidude/go-readability"
)

...

doc, err := readability.NewDocument(html)
if err != nil {
  // do something ...
}

content := doc.Content()
// do something with my content

```


Tests
-----

To run tests
`go test github.com/mauidude/go-readability`
