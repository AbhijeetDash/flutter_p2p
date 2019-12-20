## Next version

Optimizations:
- Set the minSdk Version to 16 to Support Android 4.1 and newer. Thanks to [AbdulhakimZ](https://github.com/AbdulhakimZ) [PR#5](https://github.com/mintware-de/flutter_p2p/pull/5)
## 0.1.0

Features:
- Added `WifiP2pManager.removeGroup` to be able to disconnect from the current group. Thanks to [qwales1](https://github.com/qwales1) [PR#2](https://github.com/mintware-de/flutter_p2p/pull/2)
- Added a listener for `WIFI_P2P_DISCOVERY_CHANGED_ACTION` for listening to discovery state changes group. Thanks to [qwales1](https://github.com/qwales1) [PR#4](https://github.com/mintware-de/flutter_p2p/pull/4)

Optimizations:
- Created a `ResultActionListener` which implements `WifiP2pManager.ActionListener` to remove duplicate code.

## 0.0.2
* Applied pub.dev suggestions 

## 0.0.1
* Initial Release
