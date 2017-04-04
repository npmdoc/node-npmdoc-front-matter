# api documentation for  [front-matter (v2.1.2)](https://github.com/jxson/front-matter)  [![npm package](https://img.shields.io/npm/v/npmdoc-front-matter.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-front-matter) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-front-matter.svg)](https://travis-ci.org/npmdoc/node-npmdoc-front-matter)
#### Extract YAML front matter from a string

[![NPM](https://nodei.co/npm/front-matter.png?downloads=true)](https://www.npmjs.com/package/front-matter)

[![apidoc](https://npmdoc.github.io/node-npmdoc-front-matter/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-front-matter_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-front-matter/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-front-matter/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-front-matter/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jason Campbell",
        "email": "jason@js.la",
        "url": "http://twitter.com/jxson"
    },
    "bugs": {
        "url": "https://github.com/jxson/front-matter/issues"
    },
    "contributors": [
        {
            "name": "Jason Campbell",
            "email": "jason@js.la",
            "url": "http://twitter.com/jxson"
        },
        {
            "name": "Jordan Santell",
            "email": "jsantell@gmail.com",
            "url": "https://github.com/jsantell"
        },
        {
            "name": "Kai Davenport",
            "email": "kaiyadavenport@gmail.com",
            "url": "https://github.com/binocarlos"
        },
        {
            "name": "Jean-Philippe Monette",
            "email": "contact@jpmonette.net",
            "url": "https://github.com/jpmonette"
        },
        {
            "name": "Marc-André Arseneault",
            "email": "marc-andre@arsnl.ca",
            "url": "https://github.com/arsnl"
        },
        {
            "name": "Bret Comnes",
            "email": "bcomnes@gmail.com",
            "url": "http://bret.io"
        }
    ],
    "dependencies": {
        "js-yaml": "^3.4.6"
    },
    "description": "Extract YAML front matter from a string",
    "devDependencies": {
        "brfs": "^1.4.3",
        "coveralls": "^2.11.6",
        "istanbul": "^0.3.6",
        "standard": "^6.0.4",
        "standard-format": "^2.1.0",
        "tape": "^4.4.0",
        "zuul": "^3.10.1"
    },
    "directories": {},
    "dist": {
        "shasum": "f75983b9f2f413be658c93dfd7bd8ce4078f5cdb",
        "tarball": "https://registry.npmjs.org/front-matter/-/front-matter-2.1.2.tgz"
    },
    "gitHead": "cbdbba070ddca85bff25486c264b341ebf979939",
    "homepage": "https://github.com/jxson/front-matter",
    "keywords": [
        "yaml",
        "front matter",
        "meta data"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "jxson",
            "email": "jason@greatergood.cc"
        }
    ],
    "name": "front-matter",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/jxson/front-matter.git"
    },
    "scripts": {
        "test": "make test"
    },
    "version": "2.1.2"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module front-matter](#apidoc.module.front-matter)
1.  [function <span class="apidocSignatureSpan">front-matter.</span>test (string)](#apidoc.element.front-matter.test)



# <a name="apidoc.module.front-matter"></a>[module front-matter](#apidoc.module.front-matter)

#### <a name="apidoc.element.front-matter.test"></a>[function <span class="apidocSignatureSpan">front-matter.</span>test (string)](#apidoc.element.front-matter.test)
- description and source-code
```javascript
function test(string) {
  string = string || ''

  return regex.test(string)
}
```
- example usage
```shell
...

Return a 'content' object with two properties:

* 'content.attributes' contains the extracted yaml attributes in json form
* 'content.body' contains the string contents below the yaml separators
* 'content.frontmatter' contains the original yaml string contents

# fm.test(string)

Check if a string contains a front matter header of "---" or "= yaml =". Primarily used internally but is useful outside of the
module.

Returns 'true' or 'false'

'''javascript
fm.test(string) #=> true || false
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
