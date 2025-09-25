Nessus Setup Checklist

Open the Nessus Web UI

After install, open your browser and go to:
 https://localhost:8834

It might warn about certificate → just accept the risk/continue.

Activate Nessus Essentials (Free)

Select Nessus Essentials when prompted.

Enter the activation code (you’ll get it in your email after registering on Tenable’s site).

Let Nessus Download Plugins

This can take a while (sometimes 10–20 minutes).

These plugins are what Nessus uses to detect vulnerabilities.

Create a New Scan

Click New Scan → choose Basic Network Scan.

Name it something like Localhost Scan.

Target: 127.0.0.1 (your own machine).

Run the Scan

Hit Save → Launch.

Nessus will now probe your system for vulnerabilities.
