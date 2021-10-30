---
title: Documentations
icon: fas fa-book
order: 1
published: true
---

All A31 based products from Arylic provide different types of controlling interface, including [HTTP](https://developer.arylic.com/httpapi), UPNP, TCP, UART. Most of the APIs of different connection type are same, but still have some difference.

| Function | [HTTP](https://developer.arylic.com/httpapi) | UPNP | TCP | UART |
|----------|------|------|-----|------|
| Playback Control      | [Yes](https://developer.arylic.com/httpapi/#playback-control) | Yes | Yes | Yes |
| Title and artist      | [Yes](https://developer.arylic.com/httpapi/#current-device-play-status) | Yes | Yes | Yes |
| Input source          | [Yes](https://developer.arylic.com/httpapi/#device-audio-source) | No  | Yes | Yes |
| Multiroom Control     | [Yes](https://developer.arylic.com/httpapi/#multiroom-multizone) | No  | No  | No  |
| Network Setup         | [Yes](https://developer.arylic.com/httpapi/#networking) | No  | No  | No  |
| Timer and alarm       | Yes | No  | No  | No  |
| Coverart and playlist | No  | Yes | No  | No  |
| Advanced Audio Setup  | No  | No  | Yes | Yes |

## Note

We are still working on these documents, and only the HTTPAPI part is somewhat ready. If have any question of find any mistake, please send your suggestion or feedback to tech@arylic.com. It would help a lot, thanks.
