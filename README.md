# all-fuel-transactions
HyperFuel query to save all transaction information into parquet locally.

Run with `$ cargo run --release` to download all data of all transactions on Fuel's beta-5 network as a parquet file.

Transaction data is saved in `data/transaction.parquet`

For reference, takes ~6 mins (on my laptop & internet) to download 16,601,662 transactions across 14,038,379 blocks.