---
name: 'Test scenario [#2]: Use vouchers to do a transaction'
about: Use vouchers to do a transaction
title: 'Test scenario [#2]: Use vouchers to do a transaction'
labels: scauting-testing
assignees: ''

---

Objective: Using a voucher to do a transaction is one of the core functionalities of the platform. This should be tested before every release.

# Environment

* Branch: Release **{insert version number here}**
* Database: Staging

# Pre-conditions

1. Me-app (alpha version) installed on iOS device.
2. Me-app (alpha version) installed on Android device.

# Direct URL(s)

1. https://staging.berkelland.forus.io
2. https://staging.winterswijk.forus.io
3. https://staging.oostgelre.forus.io

# Input data

1. Requester profile (e-mail)
    *
2. Provider profile (e-mail)
    * 

# Prerequisites

1. Acces to accepted provider profile
2. Sufficient amount on the voucher

# Instructions

<table>
<tr><th>Step No.</th><th>Step description</th><th>Expected result</th></tr>
<tr><td>1.</td><td>Go to the webshop, click <b>Login</b>, enter your mailaddress and click <b>Volgende</b></td><td>Login modal open with an input field to enter e-mailaddress. Login mail should be send to the mailbox. </td></tr>
<tr><td>2.</td><td>Open the mail and click the link to login</td><td>The webshop page should open and user is logged in</td></tr>
<tr><td>3.</td><td>Click on <b>Mijn vouchers</b> and click on the Budget voucher top open the voucher</td><td>Redirection the voucher page and the voucher should open with the Qr-code.</td></tr>
<tr><td>4.</td><td>Open the Me-app with provider acces and scan the Qr-code.</td><td>The provider should see a new screen with the option to enter the amount of the transaction and the possibility to confirm the transaction</td></tr>
<tr><td>5.</td><td>Enter an amount and confirm the transaction by clicking on <b>Verzoek tot betaling</b></td><td>The provider provider should see a confirmation screen with a succes message.</td></tr>
<tr><td>6.</td><td>Refresh the voucher page to check if the budget is reduced by the amount of the transaction</b></td><td>The budget of the voucher should be reduced with the amount of the transactions and the user should get a notification of this transaction.</td></tr>
</table>

# Result

* {pass / fail}

# Notes

* {any notes}
