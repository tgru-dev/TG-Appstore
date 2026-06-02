# TG Store

A custom [CasaOS](https://casaos.io) AppStore with self-hosted applications.

## Apps

| App | Description | Category |
| --- | ----------- | -------- |
| <img src="https://raw.githubusercontent.com/tgru-dev/TG-Appstore/main/Apps/cloudreve/cloudreve.png" width="32"> [Cloudreve](Apps/cloudreve) | Self-hosted cloud storage platform with multiple storage backends | Cloud |
| <img src="https://raw.githubusercontent.com/tgru-dev/TG-Appstore/main/Apps/Freddy/freddy.png" width="32"> [Fredy](Apps/Freddy) | Self-hosted real estate finder for Germany | Utilities |
| <img src="https://raw.githubusercontent.com/tgru-dev/TG-Appstore/main/Apps/seerr/seer.png" width="32"> [Seerr](Apps/seerr) | Modern media request & discovery platform | Media |
| <img src="https://raw.githubusercontent.com/tgru-dev/TG-Appstore/main/Apps/streamed2m3u/streamed2m3u.png" width="32"> [streamed2m3u](Apps/streamed2m3u) | HLS proxy for streamed.pk — live football in Jellyfin | Media |
| <img src="https://raw.githubusercontent.com/tgru-dev/TG-Appstore/main/Apps/sftpgo/sftp.png" width="32"> [SFTPGo](Apps/sftpgo) | High-performance SFTP, FTP/S & WebDAV server | Network |

## Add to CasaOS

1. Open CasaOS
2. Go to **AppStore** → click **+ Add Source**
3. Paste this URL:
   ```
   https://github.com/tgru-dev/TG-Appstore/archive/refs/heads/main.zip
   ```
4. Click **Add +**

## Contributing

Contributions are welcome. To add an app:

1. Fork this repository
2. Create a new folder under `Apps/` with your app name
3. Add a `docker-compose.yml` with valid `x-casaos` metadata
4. Test on your CasaOS instance
5. Submit a pull request

## License

MIT
