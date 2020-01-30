---
name: 'Test scenario [#3]: Sign up flow provider | URL Filter'
about: Sign up flow provider | URL Filter
title: 'Test scenario [#3]: Sign up flow provider | URL Filter'
labels: scauting-testing
assignees: ''

---

Objective: Use this template to check if the URL for the signup flow works properly.

# Environment

* Branch: Release v0.8.2
* Database: Staging

# Pre-conditions

1. Funds need to be configured
2. Three pre made filters based on the filter options.

The URL filter can be filtered based on:
- Tags
- Organization ID
- Fund ID

# Direct URL(s)
1. Tag: https://staging.forus.io/provider/sign-up?tag-sdoa 
-> 13 regelingen
2. Organization ID: https://staging.forus.io/provider/sign-up?fund_id=9 
-> Sociaal culturele en sportieve activiteiten
3. Fund_id: https://staging.forus.io/provider/sign-up?organization_id=325 
-> 5 regelingen uitgegeven door gemeente Berkelland
4. https://asdasd.nl (used for temporarily mail-address)
5. https://developers.kvk.nl/documentation/profile-v2-test (used for test kvk number)

# Input data

1. E-mail address
    * {}
2. Phone number
    * {}
3. KvK
    * {}
4. IBAN number 
    * NL60BUNQ2025316305
5. Remaining data to fill in signup flow.

# Prerequisites

1. Unregistered kvk number

# Instructions

<table>
<tr><th>Step No.</th><th>Step description</th><th>Expected result</th></tr>
<tr><td>1.</td><td>Go to one the URL described above</td><td>Page of the sign up flow should open with a step indication (1 of 7)</td></tr>
<tr><td>2.</td><td>Enter phone number, click <b>Versturen</b> , install the Me-app by using the link received on the phone and checkmark the sentence: 
<b>DE APP IS NU AAN HET DOWNLOADEN. / DE APP IS GEINSTALLEERD.</b> to go the the next step.</td><td>Sign up flow shows a succes message, phone number should receive a sms link that redirects to the app or playstore. Redirection to the next step (2 of 7) </td></tr>
<tr><td>3.</td><td>Enter requested data (mail-address twice, first and last name) an click <b>Volgende</b> button to continue</td><td>Redirection to the next page (step 3 of 7)</td></tr>
<tr><td>4.</td><td>Enter the requested data of the signup form. 1. Organisation name.<br> 2. Bank account number.<br> 3. Mail address.<br> 4. phone number.<br> 5. Website <br> 6. Organization type. <br> 7. KvK number.<br> After entering requested data click on <b>Volgende</b></td><td>Redirection to the step to add an office (4 of 7)</td></tr>
<tr><td>5.</td><td>Check address created by KvK connection. Add business hours and click <b>Volgende</b> to continue</td><td>Redirection to next step (5 of 7)</td></tr>
<tr><td>6.</td><td>Connect the profile to the app. Open Me-app, press <b>IK HEB EEN PROFIEL</b>. Enter the authorisation code displayed by the me app into the sign up flow and click <b>Volgende</b> to initiate the connection with the me app. </td><td>The Me-app should display a message with the notification about sharing bug reports. The sign up flow should go to the next step. (6 of7)</td></tr>
<tr><td>7.</td><td>Scan the QR-code with the Me-app for test purpose</td><td>Me-app displays a succes message and the sign up flow should redirect to next step (7 of 7)</td></tr>
<tr><td>8.</td><td>Choose a fund to apply on and click <b>Bevestig</b>. To continue to dashboard click on <b>Volgende</b></td><td>Modal should open with a confirmation message. After clicking <b>Bevestig</b> the modal should close and the user should see the same page with an indication of the application. After clicking <b>Volgende</b> the dashboard should open.</td></tr>
</table>

# Result

* Pass/Fail


# Notes

*
