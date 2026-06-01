# TG Store

A custom [CasaOS](https://casaos.io) AppStore with self-hosted applications.

## Apps

| App | Description | Category |
| --- | ----------- | -------- |
| [Cloudreve](Apps/cloudreve) | Self-hosted cloud storage platform with multiple storage backends | TG Store |

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
