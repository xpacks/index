# xPacks index

This project, available from [GitHub](https://github.com/xpacks/index), includes the index of all packages available in the **xPacks** repository.

The [URL of the index](http://xpacks.github.io/index/xindex.json) (to be configured in the **xPacks Manager**), is:

```
http://xpacks.github.io/index/xindex.json
```

Currently the index should point to each package `.xpack.json` file (usually to a raw GitHub location).

To simplify maintenance, the index intentionally omits versions, (the index needs to be updated only when new packages are added, or, more rarely, when packages change location or are deleted, and it does not need to be updated after any individual package gets a new release).

The **xPacks Manager** must read this index, then read the individual package files to get the up-to-date list of releases.
