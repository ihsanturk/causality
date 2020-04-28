# Causality

Causality is a causality graph helper.

## Example

- `create causality software` --> `manage the life easier`
- `make money` --> `buy goods to family` --> `be happy`
- `make money` --> `buy a new laptop` --> `be happy`

These can be thought like asking questions and answering them:

- **Q: Why `make money`?**
- A: Because `buy goods to family`.
- **Q: Why `buy goods to family` then?**
- A: Because `be happy`.

## Why

I always forgot the path to do something. Or telling someone how I did a thing.
I can remember or extract the path with this tool easily. I can alias `why` to
the command to run this tool and ask in the cli:

```
$ why learn rust
```

> - rust is the monster.
> - rust is modern.
> - rust is reliable.
> - rust has great documentation.
> - rust community is very helpful

## Roadmap

- [ ] The tool should be [POSIX](https://en.wikipedia.org/wiki/POSIX)
  compatible.
- [ ] For langugage, [Rust](https://www.rust-lang.org) is the primary option.
- [ ] Add tab completion for nodes in zsh.
- [ ] For data structure library,
  [petgraph](https://docs.rs/petgraph/0.5.0/petgraph/) would be used.
  Because it is written in Rust-lang and outputs as
  [graphviz](https://www.graphviz.org/) format.
