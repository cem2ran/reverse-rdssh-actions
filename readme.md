# reverse-rdssh-actions

## Usage
1. Download [cloudflared](https://github.com/cloudflare/cloudflared/releases/latest) to your computer.
2. Under the repository's settings, make a secrets called `PASSWORD`
3. Trigger a workflow in actions page.
4. Open terminal on your computer and run this command:\
    `CLOUDFLARED_FILE_NAME access tcp --url localhost:PORTFROMLOCAL --hostname URL_FROM_ACTIONS_LOG`
5. Done!

## Info
- Please use this for debugging~
- [Runners can run jobs for up to 6 hours](https://docs.github.com/en/actions/reference/usage-limits-billing-and-administration#usage-limits)


## License
See: https://ksp.mit-license.org