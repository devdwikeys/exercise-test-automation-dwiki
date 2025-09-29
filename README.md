#Automation Test - Dwiki Anggoro Syafitri

## Deskripsi
Project ini berisi automation test untuk 2 skenario (automation-test-dwiki\test\specs\scenariOne.js) di www.ebay.com:
1. Access a Product via category after applying multiple filters
2. Access a Product via Searchbox

## Tech Stack
- NodeJS
- WebdriverIO
- Mocha
- ChromeDriver

## Struktur Project
- Menggunakan Page Object Model (POM) agar maintainable.
- Test case ada di `test/specs/`
- Page Object ada di `test/pageobjects/`

## Cara Setup & Run
1. Install node js on your local
2. Extract folder ini.
3. Install dependencies:

#command run 
1. npx wdio run wdio.conf.js
