# Lists

Lists creation is very universal. You can group your friends and have all in one url available or you can use it for listing alliances on cexplorer.io.

## Add your pool into list

Simply create PR into a selected list.

## File structure

Json-valid simple array with pool_id (bech32)

## Automatization

Go to "Edit" section of list and you can see there "External URL". Simply add your url to json file there and we will once a day sync and update diffs.

Structure of json file is here: [https://github.com/cardanians/cexplorer.io/blob/main/examples/list_testnet.json](https://raw.githubusercontent.com/cardanians/cexplorer.io/main/examples/list_testnet.json) (its just simple json array with pool IDs)
