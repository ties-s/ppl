# Persistent package linker (ppl)

## Installation
`npm install -g ppl`

## Usage
#### Link current package
`ppl link // or npm link (these are equivalent)`  
same as original `npm link`


#### Link
`ppl link <package>`  
internally adds the package name to `package-links.json` and calls `npm link <package>`