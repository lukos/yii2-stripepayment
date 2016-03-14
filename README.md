# yii2-swiftpayment
A plugin for yii2 to use the Stripe payments provider.

#WARNING
This is currently in development and should NOT be used for production code.

##Introduction##
This plugin is to greatly simplify using the popular Stripe payments provider in yii2. Stripe provides credit card payments but also includes an aggregate Merchant Account, avoiding the need to pay for one of these yourselves and avoiding the additional costs of a dedicated Merchant Account. A dedicated Merchant account might be useful for companies with very large turnovers since the fees can be negotiated with the Merchant bank. For most of us, we don't turn over enough to pay twice for credit card payments - once for the gateway and once for the Merchant account.

##Installation##
Install with composer using the following in your composer.json ```"require" : {"lukos/yii2-stripepayment":"@dev"}``` 
