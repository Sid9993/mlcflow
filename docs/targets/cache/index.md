# Cache

Currently, the following actions are supported for cache:

## Find

`find` action is used to list the path of the cache generated while running scripts through MLC.

**Syntax**

```bash
mlc find cache --tags=<list_of_tags_used_while_running_script>
```

Examples of `find` action for `cache` target could be found inside the GitHub action workflow [here](https://github.com/mlcommons/mlcflow/blob/d0269b47021d709e0ffa7fe0db8c79635bfd9dff/.github/workflows/test-mlc-core-actions.yaml).



## Show

`show` action is used to list the path and meta data of the cache generated while running scripts through MLC.

**Syntax**

```bash
mlc show cache --tags=<list_of_tags_used_while_running_script>
```

Examples of `show` action for `cache` target could be found inside the GitHub action workflow [here](https://github.com/mlcommons/mlcflow/blob/d0269b47021d709e0ffa7fe0db8c79635bfd9dff/.github/workflows/test-mlc-core-actions.yaml).

## Rm

`rm` action is used to remove one/more caches generated while running scripts through MLC.

**Syntax**

```bash
mlc rm cache --tags=<list_of_tags_used_while_running_script>
```

A user  could delete the entire generated caches through the following command:

```bash
mlc rm cache
```

`-f` could be used to force remove caches. Without `-f`, user would be prompted for confirmation to delete a cache.

Examples of `rm` action for `cache` target could be found inside the GitHub action workflow [here](https://github.com/mlcommons/mlcflow/blob/d0269b47021d709e0ffa7fe0db8c79635bfd9dff/.github/workflows/test-mlc-core-actions.yaml).

