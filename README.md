# hcl2json WebAssembly

## Install

```bash
$ npm install -g @terrastack/hcl2json-wasm
```

## Usage

```bash
$ cat foo.tf | hcl2json

{
  "variable": [
    {
      "name": [
        {
          "description": "yeah"
        }
      ]
    }
  ]
}
```

## Use it programmatically

Not yet implemented
