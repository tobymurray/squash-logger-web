# Squash Logger download page

Web Bluetooth page for a Feather nRF52840 + ADXL375 squash swing logger: connects to the logger
("SquashLogger", Nordic UART service), downloads its flash log in acknowledged blocks, verifies the
CRC32, keeps a copy in the browser (IndexedDB), and only then allows a CRC-gated erase.

Open it in a browser with Web Bluetooth (Chrome on Android, desktop Chrome/Edge).
