# dbt_datawaves_wallet_labels


## What does this dbt project do?


This dbt project create a bunch of wallet labels using [dbt_datawaves](https://github.com/datawaves-xyz/dbt_datawaves) package. 


### Wallet labels


#### Whale

| **model** | **description**  |
|-----------|------------------|
| [nft_whale](https://github.com/datawaves-xyz/dbt_datawaves_wallet_labels/blob/master/models/labels/whale/nft_whale.sql) | Top 0.1% in the number of NFT transactions|

#### Smart Money

| **model** | **description**  |
|-----------|------------------|
| [smart_nft_trader](https://github.com/datawaves-xyz/dbt_datawaves_wallet_labels/blob/master/models/labels/smart_money/smart_nft_trader.sql) | The top 100 addresses in terms of realized profits from NFT sales. |
| [smart_nft_holder](https://github.com/datawaves-xyz/dbt_datawaves_wallet_labels/blob/master/models/labels/smart_money/smart_nft_holder.sql) | The top 100 addresses in terms of estimated profits of their current NFT portfolio. |
| [smart_nft_sweeper](https://github.com/datawaves-xyz/dbt_ethereum/blob/master/models/labels/smart_money/smart_nft_sweeper.sql) | Addresses that have profitably swept at least 5 times at or below the floor price in the last 30 days. |
| [smart_nft_trader](https://github.com/datawaves-xyz/dbt_ethereum/blob/master/models/labels/smart_money/smart_nft_trader.sql) | The top 100 addresses in terms of realized profits from NFT sales. |
| [smart_nft_golden_dog_minter](https://github.com/datawaves-xyz/dbt_ethereum/blob/master/models/labels/smart_money/smart_nft_golden_dog_minter.sql)| The top 100 addresses that have realized profits on least 2 Golden Dog Collections that were minted in the last 60 days. | 

#### NFT Collector 

| **model** | **description**  |
|-----------|------------------|
| [legendary_nft_trader](https://github.com/datawaves-xyz/dbt_datawaves_wallet_labels/blob/master/models/labels/nft_collector/legendary_nft_trader.sql) | Top 0.1% in the number of NFT transactions. |
| [epic_nft_trader](https://github.com/datawaves-xyz/dbt_datawaves_wallet_labels/blob/master/models/labels/nft_collector/epic_nft_trader.sql) | Top 1% in the number of NFT transactions. |
| [rare_nft_trader](https://github.com/datawaves-xyz/dbt_datawaves_wallet_labels/blob/master/models/labels/nft_collector/rare_nft_trader.sql) | Top 2.5% in the number of NFT transactions. |
| [uncommon_nft_trader](https://github.com/datawaves-xyz/dbt_datawaves_wallet_labels/blob/master/models/labels/nft_collector/uncommon_nft_trader.sql) | Top 10% in the number of NFT transactions. |
| [opensea_trader](https://github.com/datawaves-xyz/dbt_datawaves_wallet_labels/blob/master/models/labels/nft_collector/opensea_trader.sql) | Wallets that have transactions on OpenSea. |
| [blue_chip_nft_holder](https://github.com/datawaves-xyz/dbt_datawaves_wallet_labels/blob/master/models/labels/nft_collector/blue_chip_nft_holder.sql) | Wallets that are currently holding at least one Blue Chip NFT in their portfolio. |
| [diversified_nft_holder](https://github.com/datawaves-xyz/dbt_datawaves_wallet_labels/blob/master/models/labels/nft_collector/diversified_nft_holder.sql) | Wallets that are currently holding at least 5 collections. |

