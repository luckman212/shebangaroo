<img src="./icon.png" width="128" />

# shebangaroo

Recurses over a directory looking for scripts, and tests the ones it finds to make sure they have valid interpreters.

At the end of the run, a logfile will be opened displaying the results, including any errors found.

Use `-h` or `--help` for help.

You can specify some additional args to control the behavior, such as limiting the search scope to only shebangs containing a specific regex or string.

```
usage: shebangaroo.sh <path> [regex-search] [max_size]
- use . or leave blank to default to current dir
- example of regex search could be: `python`
- max_size: files > this value will not be checked (defaults to 512k)
```

> tangentially related to: [this topic on the Alfred forums](https://www.alfredforum.com/topic/21940-not-quite-a-bug-updating-a-workflow-should-not-automatically-enable-it-if-disabled/?do=findComment&comment=114168)
