---
name: 'Test scenario [#11]: As a user I would like to have a clear overview of all
  providers'
about: Describe this issue template's purpose here.
title: 'Test scenario [#11]: As a user I would like to have a clear overview of all
  providers'
labels: scauting-testing
assignees: ''

---

Objective: Searching and filtering is important for our users so they will have a clear overview of all offers and providers.

# Environment

* Branch: Release v0.7.0
* Database: Staging

# Pre-conditions

1. Active fund
2. Generated activation codes 

# Direct URL(s)

1. https://staging.berkelland.forus.io
2. https://asdasd.nl (used for temporarily mail-address)

# Prerequisites

# Instructions

<table>
<tr><th>Step No.</th><th>Step description</th><th>Expected result</th></tr>
<tr><td>1.</td><td>Go to the webshop and begin the activation proces by clicking on <b>START<b></td><td>Modal opens with step indication 1 of 3 and two input fields to enter and confirm the e-mailaddress</td></tr>
<tr><td>2.</td><td>Enter/confirm the mail-address and click <b>Volgende</b></td><td>Modal should display a confirmation message with the notification to confirm acces to the mailadress. An email has been sent to previously entered mailaddress</td></tr>
<tr><td>3.</td><td>Open the e-mail with step indication <b>2 of 3</b> and click the link to get redirected to the activation modal</td><td>Redirection to the activation modal with step indication <b>3 of 3</b> and an input field to enter the activation code </td></tr>
<tr><td>4.</td><td>Enter the activation code and click <b>Volgende</b>. Open mail box check if the Qr-code has been sent to the mail address.</td><td>Modal closes and the user gets redirected to the voucher page. An e-mail has been received with the Qr-code voucher.</td></tr>
<tr><td>5.</td><td>Visit the voucher page and click the <b>PRINT</b> button</td><td>Browser should open a print-preview and the option to print the voucher.</td></tr>
</table>

# Result

* {pass / fail}

# Notes

* {any notes}
