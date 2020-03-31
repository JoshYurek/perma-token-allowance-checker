
# Perma Token Allowance Checker

Many DApps have the habit of requiring you to approve effectively unlimited amount of tokens. This helps improving the user experience, as you only have to sign off an approval once and it will be enough for all future transactions.

However this also means that the DApp (or the person/entity controlling it) can at any time transfer all of your tokens, without requiring any further approval.

In addition, there is no concept of expiring approvals. Once approved, the approval will remain forever. If you do not trust a DApp or its operators anymore, there is usually no easy way to remove the approval.

Token Allowance Checker scans the complete Ethereum transaction history for ERC20-Approvals made by the provided address. It collects all ERC20 token contracts and any spender addresses that have been approved by the user in the past.

This information is displayed to the user, together with the up-to-date allowance amount.

For all entries, the user can edit or delete the allowance.

URL: https://z5vickoudlxx.arweave.net/45js6Rw7obEXhpbQ-M9nqucn9eZl369kKGW8rc5GwJw
