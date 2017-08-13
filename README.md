# mybookie by [@karosaurus](http://github.com/karosaurus)
### forked from the nifty [md-file-tree](https://github.com/michalbe/md-file-tree) by [@michalbe](https://github.com/michalbe)
Generate markdown list of all the files in a directory with a dropbox sharelink and google search link.

### How to use? ###
Install with:
```bash
 $ npm install https://github.com/karosaurus/mybookie/tarball/master
```

Then in any dir
```bash
$ insert command here
```

generated `list.md` file:

```markdown
- __books__
  - [Automated Data Collection with R - Simon Munzert.pdf](https://www.google.com)
  - [[bitme] SQL Injection Attacks and Defense, Second Edition 1597499633 (Syngress, 2012).pdf](https://www.google.com)
  - [Mastering Social Media Mining with R - Sharan Kumar Ravindran & Vikram Garg.pdf](https://www.google.com)
```

note that this script __skips__ all hidden files and directories (with `.`, like `.git` or `.gitignore`) & `node_modules` directory.


