---
name: 'Test scenario [#4]: Add products to the webshop'
about: Add products to the webshop
title: 'Test scenario [#4]: Add products to the webshop'
labels: scauting-testing
assignees: ''

---

Objective: Add products to the webshop

# Environment

* Branch: Release v.0.9.0
* Database: Staging

# Pre-conditions

1. Active fund
2. The sponsor should have accepted the provider before you add products to the webshop
2. Always follow *Test scenario [#3]* before doing this test

# Direct URL(s)

1. https://staging.forus.io/provider
2. https://berkelland.staging.forus.io/products

# Input data

1. Product information
    * Title
    * Description
    * Price
    * New price
    * Amount / unlimited stock
    * Expiration date
    * Category

# Prerequisites

1. No information

# Instructions

<table>
<tr><th>Step No.</th><th>Step description</th><th>Expected result</th></tr>
<tr><td>1.</td><td>Go to https://staging.forus.io/provider</td><td>{what a tester should see when they do that}</td></tr>
<tr><td>2.</td><td>Go to https://staging.forus.io/provider and click <b>Login</b></td><td>Login modal should open</td></tr>
<tr><td>3.</td><td>Use e-mail or Me-app to login</td><td>Did you choose e-mail? Than you should receive link to login. <br> Did you use the Me-app? Than you should be redirected to the provider dashboard</td></tr>
<tr><td>4.</td><td>Click on <b>Aanbiedingen</b> on the left side of the menu.</td><td>The page to add a product should open</td></tr>
<tr><td>5.</td><td>Enter the requested data and lick on <b>Bevestig</b></td><td>Redirection to the product overview page</td></tr>
<tr><td>6.</td><td>Go to https://staging.berkelland.forus/products and check if your product is added to the webshop</td><td>You should find your just added product.</td></tr>
</table>

# Result

* {pass / fail}

# Notes

* {any notes}
