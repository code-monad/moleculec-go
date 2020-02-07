## molecule go plugin

A plugin for the molecule serialization system to generate Go code.

### Use

```shell
$ cargo install moleculec moleculec-go
$ moleculec --language go --schema-file "your-schema-file" | gofmt > "your-go-file"
```

### Testset

all [test](./test/testset/) from [molecule](https://github.com/nervosnetwork/molecule/tree/master/test)

you can run `make gen-test` to reproduce it.

## License

Licensed under [MIT License].

[MIT License]: LICENSE
