---
tags:
  - "[git](1772767767-PUVQ.md)"
---

1. inside a repo when username/password is prompoted, input the required data.
2. run this git command so that the username/password you entered will be stored in your
local global git environment
`git config --global credential.helper store`

3. 3. manager-core (Windows and macOS) / osxkeychain (macOS) / libsecret (Linux)
These helpers store credentials securely in the OS-specific credential storage.
```windows
git config --global credential.helper manager-core
```
```macOS
git config --global credential.helper osxkeychain
```
```linux
git config --global credential.helper libsecret
```

