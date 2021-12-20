# godaddy-dynamic-dns
A script which uses GoDaddy's api to update a domain ip. Run it regularly to host on a server with a dynamic DNS.

The gd-dyndns script is copied almost directly from Tod-SoS's very helpful blog post [here](https://www.instructables.com/Quick-and-Dirty-Dynamic-DNS-Using-GoDaddy/). I'm simply hosting it in a repo to share it more easily between my devices.

To use this script:
1. Ensure you have a production API key with GoDaddy
2. Edit the script to use your own domain, hostname, and api key.
3. Set the script to run with a cron job, something like `*/10 * * * *    /usr/local/sbin/gd-dyndns > /dev/null`

That's it!
