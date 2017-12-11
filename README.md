# Persistent package linker (ppl)

## Installation
`npm install -g ppl`

## Usage
### Link current package
`ppl link`  
or  
`npm link`  
these are equivalent

### Link
`ppl link <package>`  
internally adds the package name to `package-links.json` and calls `npm link <package>`