# Kohler retreat map

An interactive version of the Destination Kohler resort map for our retreat: zoom, tap numbered places for details and directions, and (with the private event link) opt in to share your location with colleagues for a few hours.

- Positions are encrypted in the browser (AES-GCM) with a key that only exists in the event link, then relayed through public MQTT brokers (EMQX, HiveMQ).
- Sharing is opt-in, time-limited (2/4/8 h), and can be stopped at any time.
- Unofficial; based on the printed resort map.
