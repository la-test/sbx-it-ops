---
name: Onboarding or Offboarding - Text
about: Request support for the onboarding or offboarding of a team member (using plain text)
title: '[Onboarding or Offboarding]: <... as ... member>'
labels: 'access'
assignees: 'la-test/sbx'

---

<!-- IT-Ops team will need some informations to start the onboarding or offboarding -->

### For any team member

| Attribute | Required | Value | 
| -- | -- | -- |
| First name and surname (or alias) | yes | <name> |
| Existing Github username | yes | <username> |
| Favorite username (when possible) | no | <username> |
| Least Authority email address | yes | <name>@leastauthority.com |
| Private Storage email address | if relevant | <name>@private.storage |

### Only for Dev/Ops team member

* SSH public key to access the systems:
  ```
  ssh-rsa/ed25519/... ... <name>@leastauthority.com
  ```
* GPG public key to decrypt the secrets:
  ```
  -----BEGIN PGP PUBLIC KEY BLOCK-----
  ...
  -----END PGP PUBLIC KEY BLOCK-----
  ```
