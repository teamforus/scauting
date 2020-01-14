---
name: 'Test Scenario [#7]: As a sponsor I would like to have a clear overview of all
  provider applications'
about: Describe this issue template's purpose here.
title: 'Test Scenario [#7]: As a sponsor I would like to have a clear overview of
  all provider applications'
labels: scauting-testing
assignees: ''

---

# Environment

* Branch: Release **{insert release number}**
* Database: Staging

# Pre-conditions

1. Multiple configured funds
2. A batch of provider applications

# Direct URL(s)

1. https://staging.forus.io/sponsor

# Input data

1. Email address
    * 

# Instructions

<table>
<tr><th>Step No.</th><th>Step description</th><th>Expected result</th></tr>
<tr><td>1.</td><td>Go to the sponsor dashboard and click <b>Login</b></td><td>Login modal opens</td></tr>
<tr><td>2.</td><td>Enter/confirm the mail-address and click <b>Volgende</b> or scan the displayed QR Code with the me app to login</td><td>Modal should display a confirmation message about the login link. An email has been sent to previously entered mailaddress</td></tr>
<tr><td>3.</td><td>Open the e-mail with the <b>Login to the dashboard</b> title and click the link to get redirected to the sponsor dashboard</td><td>Redirection to the sponsor dashboard with the data of the organisation</td></tr>
<tr><td>4.</td><td>Click <b>Aanbieders</b> menu item to open all the provider applications</td><td><b>Aanbieder</b>tab should open with the selection of funds</td></tr>
<tr><td>5.</td><td>Select a fund to open all applications</td><td>All the provider applications of the selected fund should be visible</td></tr>
</table>

## Additional questions
In addition to the above steps, an assessment is also made of the general UX and data provided by the platform.

- [ ] Does the general user flow logically make any sense and offers it a good experience to the sponsor?
- [ ] Does the platform offer correct data?
- [ ] Does the platform offer expected data?

# Result

* {pass / fail}

# Notes

* {any notes}
