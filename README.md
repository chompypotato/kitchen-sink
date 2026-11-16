# kitchen-sink

A lightweight Isolated Web App (IWA) utility for running an isolated iframe on ChromeOS. Can unblock most sites on school Chromebooks.

## Installation

1. **Enable Isolated Web Apps:** Open your ChromeOS **Settings**, go to **Apps > Isolated Web Apps**, and toggle the setting **ON**. *(If you don't see this option, update your ChromeOS version first.)*
2. **Download the app bundle:** Download `iwa-sink.swbn` from this repository (also available via the official [ChromeOS GitHub](https://github.com/chromeos)).
3. **Launch the app:** Open the downloaded `.swbn` file to install and run it, then select **Controlled Frame**.
4. **Done!** You now have a working isolated iframe.

## Notes

* **Network restrictions:** This tool runs an isolated frame, but it will **not** bypass network-level blocks or firewalls.
* **UI scaling:** If the yellow warning bar takes up too much screen space, press `Ctrl` + `-` to zoom out and shrink it.
