* [ ] Detect when UID and GID match between host and container, skip reown process
* [ ] Disable CHAOS TXT records in .bind, .ftl, and .pihole domains: this has been submitted to upstream repo
* [ ] Fix cron issues, logrotate
* [ ] Further restrict /etc/sudoers.d/pihole 
* [ ] Reduce image size where possible
* [ ] Support HTTPS for admin and blocked pages
* [ ] Script to synchronize gravity.db across containers
* [ ] Test docker builds on GitHub before publishing
* [ ] Implement LAN forwarding
* [ ] Admin page listes on separate port than block page
* [ ] Write `$PIHOLE_WEB_HOSTNAME` to /etc/pihole/custom.list
* [ ] Example script to export DHCP lease information from dhcpd3 server
* [ ] Support for DNS-over-TLS
* [ ] Support for DNS-over-HTTPS
  * [ ] Quad9
  * [ ] NextDNS
  * [ ] Cloudflare