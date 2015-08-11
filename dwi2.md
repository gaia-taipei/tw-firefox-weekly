8/3-8/7

**[Last week]**
* [Card UI]
  * [WIP] Bug 1180154 - [Stingray] Pairing BT device in Device Deck
    - cannot get pairingReqs because gecko only allows app://bluetooth.gaiamobile.org to get pairingReqs
    - depends on Bug 1192695
  * [DONE] Bug 1186301 - [Stingray] Scanning and display BT devices in Device Deck
    - backed out and re-land
  * [DONE] Bug 1192137 - [Stingray] Remove unused script tag and link tag in Smart Home
  * [QUEUED] Bug 1180158 - [Stingray] Pin device card to Home
  * [QUEUED] Bug 1180156 - [Stingray] Display tips and help in Device Deck
  * [QUEUED] Bug 1127217 - [Stingray] Add tests for fling-player
  * [QUEUED] Bug 1141425 - [Stingray][Component] Move smart-icons to gaia-components repository
    - Not a blocker. This need UX to refine and resize icon image files first, but they don't have resource for it yet.

* [Bluetooth]
  * Study BLE GATT Server API https://wiki.mozilla.org/B2G/Bluetooth/WebBluetooth-v2/BluetoothGattServer
  * Test app
    - [WIP] connect/disonnect test for BluetoothGattServer
      - stucked because we run into b2g crashes at startLeScan (Bug 1190751)
    - [QUEUED] addService/removeService test for BluetoothGattServer

* [Hardware Key Event]
  * [QUEUED] Bug 1113461 - Add tests of blurring focus when focus is on disabled button element in System app
    - follow-up of bug 1106844


**[This week]**
* [Card UI]
  * [WIP] Bug 1180154 - [Stingray] Pairing BT device in Device Deck
    - cannot get pairingReqs because gecko only allows app://bluetooth.gaiamobile.org to get pairingReqs
    - depends on Bug 1192695
  * [WIP] Bug 1193118 - [JSDOC] Generate jsdoc of tv_apps
  * [QUEUED] Bug 1193162 - [JSDOC] write documentation of app-deck in jsdoc format
  * [QUEUED] Bug 1193163 - [JSDOC] write documentation of smart-home in jsdoc format
  * [QUEUED] Bug 1193164 - [JSDOC] write documentation of device-deck in jsdoc format

* [Bluetooth]
  * Study BLE GATT Server API https://wiki.mozilla.org/B2G/Bluetooth/WebBluetooth-v2/BluetoothGattServer
  * Test app
    - [WIP] connect/disonnect test for BluetoothGattServer
      - stucked because we run into b2g crashes at startLeScan (Bug 1190751)
    - transfer to Evan and Yong Hong

* [Hardware Key Event]
  * [QUEUED] Bug 1113461 - Add tests of blurring focus when focus is on disabled button element in System app
    - follow-up of bug 1106844
