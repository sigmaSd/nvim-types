# Nvim Types

This npm package provide types that you can use with https://github.com/TypeScriptToLua/TypeScriptToLua to write your neovim config or plugins in typescript

## Usage

1. Install this package and the required dependencies for a tstl project

```bash
npm install @sigmasd/nvim-types lua-types @typescript-to-lua/language-extensions typescript-to-lua typescript --save-dev 
```


2. Modify your `tsconfig.json` to activate the types

```json
  {
  "compilerOptions": {
    "types": ["@sigmasd/nvim-types", "@typescript-to-lua/language-extensions", "lua-types/jit"]
  }
}
```

Thats it you should be able now to run your project (`npx tstl -p tsconfig.json`) and have lsp working correctly.

## Credits

Credits to https://github.com/jose-elias-alvarez/typescript.nvim for the original idea and code
