# How do you resend a failed Bitcoin transaction?

When users send Bitcoin transactions with a really low fee value such transactions are likely to stay pending for a short time and get rejected by the network like it never happened.

When users encounter a transaction with failed (rejected) status in Vextabit it's recommended to double-check its status using some public block explorer like [https://btc.com](https://btc.com) by searching for transaction ID.

If it turns out that Vextabit shows a transaction as failed but public block explorer shows it as pending or confirmed then the problem likely is within Vextabit. Users should not attempt to resend such transactions to avoid double sends and report the issue to Vextabit wallet support for troubleshooting.

The transaction should be considered failed only if both Vextabit and public block explorer shows it as failed/rejected.
