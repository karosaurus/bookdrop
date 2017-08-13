# mybookie by [@karosaurus](http://github.com/karosaurus)
### forked from the nifty [md-file-tree](https://github.com/michalbe/md-file-tree) by [@michalbe](https://github.com/michalbe)
Generate markdown list of all the files in a directory with a dropbox sharelink and google search link.

### How to use? ###
Install with:
```bash
 $ not_yet_in_npm
```

Then in any dir
```bash
$ use_instructions
```

generated `list.md` file:

```markdown
- __michal__
  - [.fancom](michal/.fancom)
  - [.git](michal/.git)
  - [.gitignore](michal/.gitignore)
  - [.jshintignore](michal/.jshintignore)
  - [.jshintrc](michal/.jshintrc)
  - [LICENSE](michal/LICENSE)
  - [README.md](michal/README.md)
  - __bin__
    - [cli.js](michal/bin/cli.js)
  - [michal.png](michal/michal.png)
  - [node_modules](michal/node_modules)
  - [npm-debug.log](michal/npm-debug.log)
  - [package.json](michal/package.json)
  - [screen.png](michal/screen.png)
  - __scripts__
    - [assert.js](michal/scripts/assert.js)
    - [fancom.js](michal/scripts/fancom.js)
    - [jshintrc.js](michal/scripts/jshintrc.js)
    - [package-json.js](michal/scripts/package-json.js)
    - [precommit-hook.js](michal/scripts/precommit-hook.js)
    - [scripts.js](michal/scripts/scripts.js)
    - [tests.js](michal/scripts/tests.js)
  - __tests__
    - [michal-tests.js](michal/tests/michal-tests.js)
```

note that this script __skips__ all hidden files and directories (with `.`, like `.git` or `.gitignore`) & `node_modules` directory.


To install directly from github, use the following command:

npm install https://github.com/<username>/<repository>/tarball/master
