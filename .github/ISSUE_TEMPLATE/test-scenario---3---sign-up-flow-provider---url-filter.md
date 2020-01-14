---
name: 'Test scenario [#3]: Sign up flow provider | URL Filter'
about: Sign up flow provider | URL Filter
title: 'Test scenario [#3]: Sign up flow provider | URL Filter'
labels: scauting-testing
assignees: ''

---

Objective: Use this template to check if the URL for the signup flow works properly.

# Environment

* Branch: Release v0.5.1
* Database: Staging

# Pre-conditions

1. Funds need to be configured
2. Three pre made filters based on the filter options.

# Direct URL(s)

1. https://staging.berkelland.forus.io/sign
2. https://asdasd.nl (used for temporarily mail-address)
3. https://developers.kvk.nl/documentation/profile-v2-test (used for test kvk number)

# Input data

1. E-mail address
    * {}
2. Phone number
    * {}
3. KvK
    * {}
4. IBAN number 
    * {}
5. Remaining data to fill in signup flow.

# Prerequisites

1. Unregistered kvk number

# Instructions
The URL filter can be filtered based on:
- Tags
- Organization ID
- Fund ID

<table>
<tr><th>Step No.</th><th>Step description</th><th>Expected result</th></tr>
<tr><td>1.</td><td>Go to https://staging.zuidhorn.forus.io/provider/#!/sign-up</td><td>Page of the sign up flow should open with a step indication (1 of 7)</td></tr>
<tr><td>2.</td><td>Enter phone number, click **Versturen** , install the Me-app by using the link received on the phone and checkmark the sentence: 
**DE APP IS NU AAN HET DOWNLOADEN. / DE APP IS GEINSTALLEERD.** to go the the next step.</td><td>Sign up flow shows a succes message, phone number should receive a sms link that redirects to the app or playstore. Redirection to the next step (2 of 7) </td></tr>
<tr><td>3.</td><td>Enter requested data (mail-address twice, first and last name) an click **Volgende** button to continue</td><td>Redirection to the next page (step 3 of 7)</td></tr>**
<tr><td>4.</td><td>Enter the requested data of the signup form. 1. Organisation name. 2. Bank account number. 3. Mail address. 4. phone number. 5. Website 6. Organization type. 7. KvK number. After entering requested data click on **Volgende**</td><td>Redirection to the step to add an office (4 of 7)</td></tr>
<tr><td>5.</td><td>Check address created by KvK connection. Add business hours and click **Volgende** to continue</td><td>Redirection to next step (5 of 7)</td></tr>**
<tr><td>6.</td><td>Connect the profile to the app. Open Me-app, press **IK HEB EEN PROFIEL**. Enter the authorisation code displayed by the me app into the sign up flow and click **Volgende** to initiate the connection with the me app. </td><td>The Me-app should display a message with the notification about sharing bug reports. The sign up flow should go to the next step. (6 of7)</td></tr>**
<tr><td>7.</td><td>Scan the QR-code with the Me-app for test purpose</td><td>Me-app displays a succes message and the sign up flow should redirect to next step (7 of 7)</td></tr>**
<tr><td>8.</td><td>Choose a fund to apply on and click **Bevestig**. To continue to dashboard click on **Volgende**</td><td>Modal should open with a confirmation message. After clicking **Bevestig** the modal should close and the user should see the same page with an indication of the application. After clicking **Volgende** the dashboard should open.</td></tr>**
</table>

# Result

* Pass/Fail


# Notes

* 
*
