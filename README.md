# MySQL Database Setup (Docker)

## Prerequisites

- PHP (ensure you have the correct version installed)
- Docker (for MySQL database)

## Step-by-Step Guide

### Install the PHP MySQL Extension

Ensure you have the correct PHP MySQL extension installed on your local machine. Run the following command, replacing `php8.3` with your current PHP version if it's different:

```sh
sudo apt-get update
sudo apt-get install php8.3-mysql
```


## Replace the environment variable

```sh
DB_CONNECTION=mysql
DB_HOST=Your IP address
DB_PORT=3310
DB_DATABASE=Your database
DB_USERNAME=root
DB_PASSWORD=root
```

