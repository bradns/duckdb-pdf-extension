# DuckDB PDF extension
An extension to DuckDB to allow the reading of financial data stored in PDF files. This is primarily aimed at those who wish to ingest and query large amounts of transaction data from banks or other financial institutions. The expectation is that the PDF files would largely consist of rows that contain a timestamp, a description and a transaction amount, most likely denominated in some currency.


## Building
As with any project based on the DuckDB Rust Extension template, it is built with:
```shell
make configure
make debug
```

Then, to test the extension run:
```shell
make test_debug
```