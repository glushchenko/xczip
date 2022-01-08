# xczip

xczip - create xcframework zip archive for swift binary package. 
Creates an xcframework archive with a stable checksum that does not change when the build is repeated.

### Installation

#### Homebrew

Run the following command to install using [Homebrew](https://brew.sh/):

```console
$ brew install DimaRU/formulae/xczip
```

### Usage:
```
OVERVIEW: Create xcframework zip archive for swift binary package.

USAGE: xczip <path> --date <date> [--time <time>] [--output-path <output-path>] [--comment <comment>]

ARGUMENTS:
  <path>                  Path to xcframework.

OPTIONS:
  --date <date>           Force compressed files modification date.
        Date format must be M-d-yyyy
  --time <time>           Force compressed files modification time.
        Time format must be hh:mm:ss
  -o, --output-path <output-path>
                          Path for created archive.
  -c, --comment <comment> Add comment to zip file.
  --version               Show the version.
  -h, --help              Show help information.
```
