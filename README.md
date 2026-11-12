# Rack Hub

Local classroom dashboard for Raspberry Pi, Apache and PHP 8. Students view notices, task instructions and pod-specific service links. Teachers manage posts through a protected administration page. Work is submitted through the school's existing assessment portal.

## Download on the Raspberry Pi

```sh
git clone https://github.com/EdugenIO/rack-hub.git
cd rack-hub
```

Follow [INSTALL.md](INSTALL.md) for installation, teacher authentication, HTTPS and classroom checks. Serve only the application files as instructed; keep content and credentials outside the web root.

Includes Alpha/Bravo/Charlie selection, phpMyAdmin and DVWA links, an IIS games library and an unpublished ioquake3 connection template. No external frontend dependencies, student accounts or submission storage.

This source has not yet been runtime-tested on the rack. Complete the acceptance checks before classroom use. Keep DVWA isolated from the hub and teacher data.
