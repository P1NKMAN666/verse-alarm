# Rise & Verse 0.2.0 — Redmi Pad SE

1. Sa browser ng tablet, [i-download ang Rise & Verse APK](https://github.com/P1NKMAN666/verse-alarm/raw/refs/heads/main/downloads/RiseAndVerse-0.2.0-debug.apk).
2. Buksan ang APK at piliin ang **Update/Install**. Hindi kailangang i-uninstall ang lumang Verse Alarm; pareho ang application ID at signing certificate para mapanatili ang alarms at settings.
3. Buksan ang **Rise & Verse**. Sa Settings → Permissions & alarm setup, payagan ang Notifications, Alarms & reminders, at Full-screen alarms kung hihingin.
4. Sa HyperOS settings ng app, piliin ang **No restrictions** sa battery usage at i-enable ang **Background autostart** kung available. Kung may lock option sa app card sa Recent Apps, maaari rin itong gamitin. Maaaring magkaiba ang pangalan/lokasyon ng menus sa tablet.
5. Payagan ang lock-screen notifications at tingnan ang alarm volume.
6. Gumawa ng alarm ilang minuto mula ngayon. Habang gising, subukang mag-Home, mag-clear ng Recent Apps at i-lock ang screen. Dapat manatili ang ringing state. Kapag pinatay ang process, maaaring may maikling sound gap habang nire-recover ang alarm.

## Mga bago

- Pangalan: **Rise & Verse**.
- Kailangan ang buong verse, **isang space**, at ang Bible reference sa dulo. Kopyahin nang eksakto ang nakadisplay, pati case at punctuation.
- Sa pag-add o pag-edit ng alarm, puwedeng i-scroll ang hours/minutes o pindutin ang **Type time instead / I-type ang oras**. Gumagamit ito ng 24-hour time, mula `00:00` hanggang `23:59`.
- May recovery para sa hindi pa tapos na alarm kapag nawala ang app process. Hindi nire-restart ng recovery ang alarm na na-snooze o nakumpleto na.

Testing build pa ito. Hindi kayang pigilan ng app ang Force stop sa system settings, pag-off ng tablet, o lahat ng HyperOS restrictions. Kailangan pang makumpirma ang aktuwal na behavior sa iyong Redmi Pad SE. Walang kiosk/device-owner setup.
