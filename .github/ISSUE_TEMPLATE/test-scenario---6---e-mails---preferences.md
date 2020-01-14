---
name: 'Test Scenario [#6]: E-mails & Preferences'
about: E-mails & Preferences
title: E-mails & Preferences
labels: scauting-testing
assignees: ''

---

Objective: Activating and printing the voucher code is one of the core functionalities of the platform. This should be tested before every release.

# Environment

* Branch: Release **{insert release number}**
* Database: Staging

# Pre-conditions

1. Profile with all roles and acces levels (to receive all mails)
2. 

# Direct URL(s)

1. https://staging.zuidhorn.forus.io
2. https://asdasd.nl (used for temporarily mail-address)

# Input data

1. Email address
    * {insert mail-address}

# Prerequisites

1. 

# Instructions
To get a clear overview, we have separated the emails based on the roles represented in the platform. In addition, the tester should always check if the e-mail is a **must have**, emails with this check mark should always work to guarantee the usability of the platform.

Please use the following symbols to indicate the result of the test.
:white_check_mark: : **Pass**
:x: : **Fail**

# E-mails

## All
|     E-mail    | Must have | Result
|:-------------:|:---------:|--:|
| Link to login |   <ul><li> -[x] </li></ul>   |   |

## Requester
|       E-mail       | Must have |    Result |
|:------------------:|:---------:|----------:|
| Payment succesfull |     No    |  |
| Fund expires       |     No    |  |
| Voucher sent       |    <ul><li> -[x] </li></ul>    | |

## Provider
|       E-mail      | Must have |    Result |
|:-----------------:|:---------:|----------:|
| Fund Started      |     No    |  |
| New fund created  |     No    |  |
| Provider accepted |     No    |  |
| Provider rejected |     No    |  |
| Product sold out  |     No    |  |
| Product bought    |     No    |  |

## Sponsor
|      E-mail      | Must have |    Result |
|:----------------:|:---------:|----------:|
| Provider applied |     No    |  |
| Product added    |     No    |  |
| Balance warning  |     <ul><li> -[x] </li></ul>    |  |

## Validator
|         E-mail         | Must have | Result |
|:----------------------:|:---------:|-------:|
| You added as validator |     No    |        |
| New validation request |     No    |        |

# Overall result

* {pass / fail}

# Notes

* {any notes}
