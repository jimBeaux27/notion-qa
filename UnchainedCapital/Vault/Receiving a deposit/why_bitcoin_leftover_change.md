# Why is my leftover bitcoin sent to a new address when I withdraw?


A change address is part of your vault, and the remaining balance of a partial withdrawal is sent there.
This is the way that bitcoin handles "change." When you make a transaction, you may have more bitcoin in your wallet than the amount you want to send. The difference is sent to a change address controlled by the same keys as your vault. This ensures that the sender retains control of any remaining funds and prevents them from being lost. Change addresses increase privacy by creating a new address for each transaction, which makes it harder for others to track the movement of funds. You can read more about change addresses in this bitcoin Stack Exchange article.

Tip: You can verify this new address on your devices to confirm it belongs to your multisig quorum.

 


