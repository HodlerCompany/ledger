# Qredit Ledger
Qredit wallet application for Ledger Blue and Nano S

Under development

## Install Development Environment
- Install ledger vagrant https://github.com/fix/ledger-vagrant
- Clone this repo under `apps/`
- Connect to the vagrant machine `vagrant ssh`
- Move to the app `cd apps/qredit-ledger`
- Connect your ledger Nano S
- Install the app `sh ./rebuild.sh` (ie. build, delete and load app on ledger)

## TODO
- [x] Make derivation path working
- [x] Generate correct address
- [-] Parse serialized transactions
  - [x] Type 1
  - [x] Type 2
  - [ ] Type 3
  - [ ] Type 4
  - [ ] Type 5
- [x] Sign transaction
- [x] Make network agnostic

## Security

If you discover a security vulnerability within this application, please send an e-mail to nayiem@qredit.io. All security vulnerabilities will be promptly addressed.

## License

The MIT License (MIT)
