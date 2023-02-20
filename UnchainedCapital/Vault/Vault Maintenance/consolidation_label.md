# What is a consolidation transaction?



Consolidation transactions are required when you've received a high number of vault deposits without making any withdrawals
Over time, UTXOs (unspent transaction outputs) accumulate in vaults as you make bitcoin deposits—every deposit is a UTXO, which you can think of as a chunk of data representing a specific amount of bitcoin. Every time you make a withdrawal from a vault, your UTXOs consolidate into one chunk of data and move to a new, fresh address. 

If you are saving in bitcoin for the long-term, you may not be making many withdrawals from your vault. If you also make multiple deposits, this results in UTXOs stacking up over time. A high number of UTXOs at a single address can lead to a few problems, including:

Hardware wallets either have difficulty with signing or cannot sign a given transaction due to memory constraints; and
Higher than average fees when you do ultimately conduct a withdrawal. UTXOs are data. The more data you need to move during a transaction, the more expensive the transaction is because miners charge bitcoin transaction fees per byte.
To fix this, you will need to make regular consolidation transactions. Simply put, any withdrawal or transfer that you conduct from your vault is a consolidation transaction. Making any withdrawal from your vault does two things.

First, it moves an amount of bitcoin to another address. Second, and most importantly in this case, your vault consolidates the remaining UTXOs at a new change address. Using one transaction, you take multiple UTXOs and combine them into one single UTXO at a new address.

How to make a consolidation transaction
Finally, if you’re interested in learning about this concept in greater detail, see our blog articles by concierge technical director Tom Honzik: what UTXOs are and why having too many UTXOs can be problematic.

