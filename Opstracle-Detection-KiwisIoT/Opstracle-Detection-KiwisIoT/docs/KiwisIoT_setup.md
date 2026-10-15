# KiwisIoT Dashboard Setup

1. Log in at https://kiwisiot.com.
2. Open **My Panels** and create a new panel named **Opstracle Detection with KiwisIoT**.
3. Add a **Label** widget (Text display widget) to show the distance.
4. Copy the panel's **Topic ID** (format: `dash_XXXXXXXXXXXXX`).
5. Paste the Topic ID into `topic` in `src/sketch_Opstracle_Detection.ino`.
6. Upload the sketch and confirm the panel shows **Online**.

The Label widget displays the latest distance in centimeters.
