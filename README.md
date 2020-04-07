# WIP: AlphaWallet integration
Currently blocked on `getLendingPool` not returning an address

## Testing & Debugging
1. On Mac:
    ```
    brew install xmlsectool
    brew install xmlstarlet xmllint
    ```

2. Delete the `aDAI.canonicalized.xml` file and run:
    ```
    make aDai/aDAI.canonicalized.xml
    ```

3. Airdrop the new `aDAI.canonicalized.xml` to your iPhone and open with AlphaWallet app

## Information
See [TokenScript examples directory](https://github.com/AlphaWallet/TokenScript-Examples)
