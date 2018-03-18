# Enable sound with alsamixer

1. Test the speakers

        speaker-test -D default:PHC -c 8

2. Edit (or create) alse-base.conf

        sudo nano /etc/modprobe.d/alsa-base.conf

3. Add the line :

        options snd_hda_intel index=1

4. Reboot

        reboot
