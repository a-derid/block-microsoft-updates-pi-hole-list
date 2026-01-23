# block-microsoft-updates-pi-hole-list
A simple Pi-hole blocklist for Windows Update, Microsoft Store, and Start Menu "Suggestions" (ads). Designed to keep Windows quiet and stop unpredictable updates.

How to use it?
Just copy url to txt file and add the full list

A few things to keep in mind:
This will stop security patches (!!!). If you care about keeping the PC safe, you should probably unblock these time to time or better found a tool or way comfortable for you to install security patches only.

Also windows likes to try and bypass local dns by talking to google or cloudflare directly. if you see updates still getting through, you might need to block outgoing port 53 on your router for everything except the pi-hole.

If you use office 365 or other microsoft apps, some of the assets domains might cause issues with icons or small features. if something breaks, check your logs and whitelist the specific domain causing the problem.
