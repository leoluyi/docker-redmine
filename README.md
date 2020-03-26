# README

Docker Image for Redmine [sameersbn/docker-redmine](https://github.com/sameersbn/docker-redmine)

## Get Started

```
docker-compose up -d
```


## Backup Data

**Configuration Parameters for `--env-file`**

- `REDMINE_BACKUPS_DIR`
- `REDMINE_BACKUP_SCHEDULE`

## Install Themes

TBD

## Install Plugins

Plugins should be installed in the plugins directory at the data store.

```sh
mkdir -p /srv/docker/redmine/redmine/plugins
```

### Plugin list

- Redmine Banner plugin
- Redmine Close Issue Button Plugin
- Image Clipboard Paste
- Redmine Issue Templates plugin
- Redmine Lightbox 2
- Redmine Mentions
- Redmine Omniauth Google plugin
    - Checkout the Google OAuth Login documentation

![google_auth](/assets/img/google-OAuth-login.png)

## References

- https://github.com/sameersbn/docker-redmine
- https://github.com/bitnami/bitnami-docker-redmine
