# json-to-frontmatter-yaml
A small json to frontmatter yaml script using the grey-matter library (Used with the Hugo static website generator, but if you want to use it for other purposes, I am sure you can)


Use by adjusting the config section at the top of the script 


### Prerequisites

- node & npm
- grey-matter

### Installing & Running

- Run `npm install` to install dependencies
- Run `node convert.js` to convert files

#### Commands

There is 1 available command:

- `node convert.js` (Converts the file and creates a second index file named index.md.md that you can rename yourself)
- `node convert.js replace` (Replace original index.md with new and rename original as index_old.md .)


Flags:
- `-c FILE.json` or `--configFile FILE.json` flag to override default config (check config-example.json)
