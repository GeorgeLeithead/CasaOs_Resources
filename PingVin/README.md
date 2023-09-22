# PingVIN
Pingvin Share is self-hosted file sharing platform and an alternative for WeTransfer.

## ✨ Features

- Share files using a link
- Unlimited file size (restricted only by disk space)
- Set an expiration date for shares
- Secure shares with visitor limits and passwords
- Email recipients
- Integration with ClamAV for security scans

## Icon
```text
https://github.com/GeorgeLeithead/CasaOs_Resources/blob/main/PingVin/pingvin.png?raw=true
```

## 🐧 Get to know Pingvin Share

- [Demo](https://pingvin-share.dev.eliasschneider.com)
- [Review by DB Tech](https://www.youtube.com/watch?v=rWwNeZCOPJA)

### Configuration

You can customize Pingvin Share by going to the configuration page in your admin dashboard.

#### Environment variables

For installation specific configuration, you can use environment variables. The following variables are available:

##### Backend

| Variable         | Default Value                                      | Description                            |
| ---------------- | -------------------------------------------------- | -------------------------------------- |
| `PORT`           | `8080`                                             | The port on which the backend listens. |
| `DATABASE_URL`   | `file:../data/pingvin-share.db?connection_limit=1` | The URL of the SQLite database.        |
| `DATA_DIRECTORY` | `./data`                                           | The directory where data is stored.    |
| `CLAMAV_HOST`    | `127.0.0.1`                                        | The IP address of the ClamAV server.   |
| `CLAMAV_PORT`    | `3310`                                             | The port number of the ClamAV server.  |

##### Frontend

| Variable  | Default Value           | Description                              |
| --------- | ----------------------- | ---------------------------------------- |
| `PORT`    | `3000`                  | The port on which the frontend listens.  |
| `API_URL` | `http://localhost:8080` | The URL of the backend for the frontend. |