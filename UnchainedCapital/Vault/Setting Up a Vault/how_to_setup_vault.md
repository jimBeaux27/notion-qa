# How do I create a multisig vault?
Sign up for an account, get Tier 2- approved, upload your keys, and create your vault.
To get started with an Unchained client-controlled vault, you have two options:

Sign up for Concierge Onboarding and let us walk you through everything!
Create a vault yourself.
If you would like to use our Concierge Onboarding service, navigate to the proper page on our website (Personal or Business) and fill out the form to get started.

With Concierge, you get an onboarding call with a vault specialist, training on how to use our open-source external recovery tools, exclusive access to continuing education webinars, ongoing support, and 30 days of access to our Premium Support service. With Premium Support, you can get expert help well beyond the initial setup with advanced technical support.

To create a vault yourself, you'll need to create an Unchained account, get approved for a Tier 2 account, upload your keys, and then create your vault. Keep reading for more.


What you’ll need
To create an Unchained Capital vault, you’ll need to prepare the following:

Two hardware wallets (Unchained supports Trezor, Ledger, and Coldcard)
A PC or Mac with USB ports to connect your hardware wallets
A safe place to store your multisig wallet config file (a 1Password or LastPass account will do)
How to create a do-it-yourself Unchained multisig vault
You can find the exhaustive version of the below step-by-step guide, including screenshots and more information, on the Unchained Capital blog.

You can also follow the abridged steps below to first upload your two wallet keys, create your own vault, and then properly back up your multisig wallet configuration file.

How to upload your two wallet keys
Create an Unchained account.
Prepare your hardware wallets by installing their firmware and creating a new wallet using your wallet manufacturer’s official software. If you aren’t comfortable initializing your wallets yourself, we recommend Concierge Onboarding.
Properly back up two seed phrases—one for each initialized hardware wallet (see our operational security guide for more details).
Sign in to your new Unchained account and click Keys to view the list of keys in your account.
Click Upload New Key.
Give your first key a name. Anything will do, but keep it simple and easy to remember. Don’t reveal too much information with these names; names that reveal anything about the device’s security (such as location) or the physical device itself (like Black Trezor) are not recommended.
Choose the type of wallet you’re uploading your key from: Ledger, Trezor, or Coldcard. 
Click "Connect to [wallet brand]". Export the extended public key (xpub) from your first hardware device as prompted.
Review your key information on the Review Key page: the Key Name, the Currency (Unchained only supports BTC), the BIP32 Path (this is the default path unless you have changed it using advanced settings, which is not recommended for most users), and the Public Key itself.
Click Create to finalize the key add process.
Click on Upload New Key on the Keys page once again and follow steps 5 through 9 to upload the extended public key (xpub) from your second hardware wallet.
That's it! You've finished uploading your two keys.
How to create an Unchained vault
Note: You cannot proceed with the vault creation process until you have been approved for Tier 2.

Navigate to the Vaults page in your Unchained account and click Create a New Vault.
Choose your custody model. The default custody model involves you holding two keys with Unchained holding the third. This model makes sense for most bitcoiners seeking to get the benefits of a multisig wallet with the fewest compromises.
Choose the default signers. You can choose between the default being Sign On Your Own (you using both of your hardware wallets to sign transactions), or Unchained Cosigns (you signing with one key and paying Unchained a fee to sign with the Unchained key). You can always change this later.
Name your vault, select the two keys you uploaded to your Unchained account earlier, review your vault, and click Create.
That's it! You now have a functional Unchained vault.
Safely store your wallet configuration file
You also need to ensure you have properly stored your multisig wallet configuration file. 

Read our blog article to learn what a multisig wallet configuration file is and why it is important.
Follow our guide that explains how to locate and download your wallet configuration file.
We've established some best practices around the storage of this file; be sure to read our full guide on how to do this properly. 
That's it—you're now a wallet config file expert!
At the end of this process, you should now have two hardware devices and two backup seed phrases (for recovering your wallets if you ever lose the devices themselves!), a fully-functional Unchained Capital multisig vault, and a backed-up wallet config file. If any of that doesn't sound like you, we can help you make it happen with Concierge Onboarding.
