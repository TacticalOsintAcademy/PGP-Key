# Tactical OSINT Academy PGP Key
## Fingerprint: 6A3D 4C44 3CDE D0C4 8955  BD05 7168 FAFD BECC BF3
### Encrypting Communications for added security

<br>

There is a lot of software you can use for encrypting emails:

- We particularly like [GPG Tools](https://gpgtools.org), the current newest version of GPG Mail is `GPG Suite 2022.1`, so make sure it's up to date.

- We use ProtonMail Business therefore,if you are a Protonmail user comms are automatically encrypted.
- We can still receive encrypted emails from other users with ProtonBridge combined wih GPG Tools, so as long as you add our Public Key to your keychain, you can send us an encrypted email from any address.

Ways of adding our key to your GPG Keychain:

1. Go [here](https://github.com/TacticalOsintAcademy/PGP-Key/blob/master/Training%40tactical-osint-academy.com%20(BECCBF3F)%20–%20Public.asc) to our public key .asc file , highlight the whole PGP Key block and click copy, GPG Keychain should detect the PUB key and ask you if you want to save it.
2. Go to this Open PGP Keys site: https://keys.openpgp.org, search for our key with our Fingerprint: `6A3D4C443CDED0C48955BD057168FAFDBECCBF3F`, and once it finds it, you can download straight from the website.
3. Use the [Prot1ntelligence Python tool](https://github.com/C3n7ral051nt4g3ncy/Prot1ntelligence) that we made (has 3 modules that we forked from ProtOSINT)

As you can see below, the tool discovered our ECC Curve Key (Elliptic Curve Cryptography OpenPGP), with creation date and time:

<br>

<img width="433" src="https://user-images.githubusercontent.com/104733166/186697838-6ab09476-dca7-4684-ab53-11b7481819a6.png">
