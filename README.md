# Dockerfile

- Tree Sitter: [tree-sitter-dockerfile](https://github.com/camdencheek/tree-sitter-dockerfile)
- Language Server: [dockerfile-language-server](https://github.com/rcjsuen/dockerfile-language-server)

Now zed support match [glob](https://github.com/zed-industries/zed/pull/12043). ex:

```json
{
  "file_types": {
    "Dockerfile": [ "Dockerfile.*" ]
  }
}
```

Prev PR: https://github.com/zed-industries/zed/pull/7977 & https://github.com/zed-industries/zed/issues/6905
