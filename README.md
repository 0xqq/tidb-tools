# tidb-tools

tidb-tools are some useful tool collections for [TiDB](https://github.com/pingcap/tidb).

## How to build

```
make build # build all tools

make importer # build importer

make checker # build checker

make sync_diff_inspector # build sync_diff_inspector

make binlogctl  # build binlogctl
```

When tidb-tools are built successfully, you can find the binary in the `bin` directory.

## Tool list

- [importer](./importer)

    A tool for generating and inserting data to any database which is compatible with the MySQL protocol, like MySQL and TiDB.

- [checker](./checker)

    A tool for checking the compatibility of an existing MySQL database with TiDB.

- [sync_diff_inspector](./sync_diff_inspector)

    A tool for comparing two databases' data and outputting a brief report about the differences.

- [binlogctl](./tidb_binlog/binlogctl)

    A tool for performing some tidb-binlog related operations, like querying the status of Pump/Drainer and unregistering some Pump/Drainer.


## License

Apache 2.0 license. See the [LICENSE](./LICENSE) file for details.
