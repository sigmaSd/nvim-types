# Nvim Types

This npm package provide types that you can use with https://github.com/TypeScriptToLua/TypeScriptToLua to write your neovim config or plugins in typescript

## Usage

1. Get this package from npm

```bash
npm install @ts-defold/types --save-dev 
```

2. Modify your `tsconfig.json`

```diff
{
  "compilerOptions": {
+    "types": ["@sigmasd/nvim-types"]
  }
}
```

## Credits

Credits to https://github.com/jose-elias-alvarez/typescript.nvim for the original idea and code
