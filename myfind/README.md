# Myfind

## Python

A tool to search files/directories for a search term

Used to find subject within study notes

### USAGE

```
findterm <search-term> [<directory>] [<file types,..,..>]

DEFAULTS:
Directory: pwd / {os.getcwd()}
Filetypes: 'txt' (.txt always included)

EXAMPLE:
findterm "jquery"
findterm "jquery" ~/WebDev/Learning
findterm "jquery" ~/WebDev/Learning .js .html .css
```

