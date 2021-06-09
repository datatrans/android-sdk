## [1.3.1] - 2021-06-09

### Fixed

- Fix card flow when using authenticationOnly=true in server-to-server init call
- Improve validation for card expiration dates
- Do not clear content of card expiration date and CVV field when clicking on them while editing
- Fix corners of sheet on tablets
- Fix height difference when entering a card with invalid prefix

## [1.3.0] - 2021-05-21

### Added

- Use language from server-to-server init call

### Changed

- Separated option "GooglePayConfig.showLargeButton" into two options: show Google Pay native button and "fake" Google Pay token

### Fixed

- Block UI when loader is shown
- Fix authorization when "createAlias": true is sent in server-to-server init call
- Fix fragment_close_exit.xml and fragment_open_enter.xml animation files
- Support missing "autoSettle" flag in server-to-server init call
- Fix Google Pay callback

## [1.2.0] - 2021-05-03

### Added

- Card tokenization for PCI proxy

## [1.1.0] - 2021-04-26

### Added

- Boncard/Lunch-Check
- Additional Byjuno parameters support

### Fixed

- Do not obfuscate ExternalProcessRelayActivity

## [1.0.0] - 2021-04-16

### Added

- Dynamic navigable sheet
- UI for payment method selection
- UI for saved tokens selection
- UI for card input
- Card Scanner
- Normal payments
- Payments creating tokens for future payments
- Payments using a token
- Requesting a token for future payments
- App-to-App switches for TWINT & PostFinance
- Customizable colors
- Accessibility features

#### Supported Payment Methods
- American Express
- Byjuno
- Diners
- Discover
- Google Pay
- JCB
- MasterCard
- MyOne
- PayPal
- Paysafecard
- PostFinance Card
- PostFinance E-Finance
- Powerpay
- Reka
- Samsung Pay
- SEPA (ELV)
- Supercard
- Swissbilling
- Swisscom Pay
- SwissPass
- Twint
- UATP
- Visa

[1.3.0]: https://github.com/datatrans/android-sdk/releases/tag/1.3.0
[1.2.0]: https://github.com/datatrans/android-sdk/releases/tag/1.2.0
[1.1.0]: https://github.com/datatrans/android-sdk/releases/tag/1.1.0
[1.0.0]: https://github.com/datatrans/android-sdk/releases/tag/1.0.0
