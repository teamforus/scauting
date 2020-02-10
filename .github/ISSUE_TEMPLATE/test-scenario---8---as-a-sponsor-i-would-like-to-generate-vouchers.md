---
name: 'Test Scenario [#8]: As a sponsor I would like to generate vouchers'
about: As a sponsor I would like to generate vouchers
title: 'Test Scenario [#8]: As a sponsor I would like to generate vouchers'
labels: scauting-testing
assignees: ''

---

Objective: As a sponsor I would like to generate vouchers

# Environment

* Branch: Release v0.9.0
* Database: Staging

# Pre-conditions

1. Multiple configured funds
2. A batch of provider applications

# Direct URL(s)

1. https://staging.forus.io/sponsor

# Input data

1. Email address
    * staging+sdoa@forus.io

# Instructions

<table>
<tr><th>Step No.</th><th>Step description</th><th>Expected result</th></tr>
<tr><td>1.</td><td>Go to the sponsor dashboard and click <b>Login</b></td><td>Login modal opens</td></tr>
<tr><td>2.</td><td>Enter/confirm the mail-address and click <b>Volgende</b> or scan the displayed QR Code with the me app to login</td><td>Modal should display a confirmation message about the login link. An email has been sent to previously entered mailaddress</td></tr>
<tr><td>3.</td><td>Open the e-mail with the <b>Login to the dashboard</b> title and click the link to get redirected to the sponsor dashboard</td><td>Redirection to the sponsor dashboard with the data of the organisation</td></tr>
<tr><td>4.</td><td>Click <b>Aanbieders</b> menu item to open all the provider applications</td><td><b>Aanbieder</b>tab should open with the selection of funds</td></tr>
<tr><td>5.</td><td></td></tr>
</table>

# Result

* {pass / fail}

# Notes

* {any notes}
