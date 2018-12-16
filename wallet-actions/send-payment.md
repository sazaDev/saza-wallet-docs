---
description: Allows you to send Stellar Lumens (XLM) or custom assets to other accounts
---

# Send Payment

Sending payments is straightforward. Just enter the following details

* From: Select the account the payment is originating from
* To: Select or enter the recipient.
* Amount: quantity of tokens to send
* Select the token: Choose between the tokens on your account or enter a custom token
* Select the memo type and enter the memo
* [Sign transaction](sign-transaction.md) and submit

{% hint style="info" %}
Recipient can be any of the following

* Stellar public key
* Federated address
* Email address. Learn more below
{% endhint %}

{% hint style="info" %}
Note that when sending a custom token from the issuing account, the token will not be listed in the dropdown. You must enter the asset code and issuer of the token manually
{% endhint %}

{% hint style="info" %}
Sending payments to an account that is not funded will automatically fund the account in XLM with the amount entered
{% endhint %}

{% hint style="info" %}
Most exchanges require a memo. When sending payment to an exchange, confirm the type of memo required from the exchange. In most cases it will be either MEMO\_TEXT or MEMO\_ID
{% endhint %}

## Sending payments to an email address

Saza enables you to send payments to an email address. It is a cool way to invite users to try out the Stellar network. 

When a payment is sent to an email address, the following occurs:

* A new stellar account is created with the sent amount
* The sender and recipient are signatories to the newly created account
* A notification is sent to the email with details on how to claim the lumens.

{% hint style="info" %}
* Only XLM can be sent to an email address.
* The sender can cancel the transaction and reclaim the lumens if it has not been claimed by the recipient.
{% endhint %}

