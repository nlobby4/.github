<!-- ? ############################################# -->
<!-- ? Header -->

<h1 align="center">

![nlobby4][logo]![security][banner]

</h1>

<!-- ? ############################################# -->
<!-- ? Main Area -->

If you discover a security vulnerability, exploit, or any potentially harmful
behavior in this project, **please do not open a public issue**. Instead, report
it **privately** using GitHub Private Vulnerability Reporting:

Open a private report from this repository's **Issues** tab using **Report a
vulnerability**.

If you cannot use GitHub private reporting, use one of the following channels:

- **Email**: Send details to [contact@nlobby4.org](mailto:contact@nlobby4.org)
- **Discord**: [Join our Discord server](https://discord.gg/flockmod/)

We encourage you to encrypt reports done via email by using our public PGP key:

- **PGP public key**: [pgp-key.txt](https://nlobby4.org/.well-known/pgp-key.txt)
- **Fingerprint**: `FCD1 94A1 5BA8 6D76 F4D5  8677 75C6 0A59 5924 1E99`

For security researchers, we provide the following resources to facilitate
responsible disclosure:

- **Security metadata**:
  [security.txt](https://nlobby4.org/.well-known/security.txt)
- **Signature**:
  [security.txt.asc](https://nlobby4.org/.well-known/security.txt.asc)
- **Security policy**:
  [security-policy.txt](https://nlobby4.org/.well-known/security-policy.txt)

Verification (example):

```bash
gpg --import pgp-key.txt
gpg --fingerprint contact@nlobby4.org
# Confirm output matches: FCD1 94A1 5BA8 6D76 F4D5  8677 75C6 0A59 5924 1E99
gpg --verify security.txt.asc security.txt
```

---

<!-- ? ############################################# -->
<!-- ? Footer -->

<div align="right">

![footer][footer]

</div>

<!-- ? ############################################# -->
<!-- ? References -->

[logo]:
  https://media.githubusercontent.com/media/nlobby4/organization/refs/heads/main/project/repo/security/logo-security.png
[banner]:
  https://media.githubusercontent.com/media/nlobby4/organization/refs/heads/main/project/repo/security/banner-security.png
[footer]:
  https://media.githubusercontent.com/media/nlobby4/organization/refs/heads/main/project/repo/security/footer-security.png
