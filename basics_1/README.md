# Change Your Home IP

This project contains a Bash script that configures local IP resolution rules on an Ubuntu system by modifying the `/etc/hosts` file.

## Requirements

The script modifies the host configuration so that:
- `localhost` resolves to `127.0.0.2` (instead of `127.0.0.1`).
- `facebook.com` resolves to `8.8.8.8` (instead of its standard IP address).

## File Overview

- `0-change_your_home_IP`: Bash script that updates `/etc/hosts` with the custom IP entries.

## Usage

1. **Make the script executable:**
   ```bash
   chmod +x 0-change_your_home_IP
