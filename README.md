# 30minToTurnOff
This script will wait for 30 minutes (1800 seconds) and then shut down the computer immediately.

    @echo off
    timeout /t 1800 /nobreak
    shutdown /s /f /t 0
