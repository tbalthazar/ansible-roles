# Nextcloud Role

## Config Vars

- nextcloud_https: "enabled" or "disabled", default: "disabled"
- nextcloud_db_docker_image_tag
- nextcloud_postgres_user (default "nextcloud")
- nextcloud_postgres_password
- nextcloud_postgres_db (default "nextcloud")
- nextcloud_domain
- nextcloud_redis_password
- nextcloud_main_storage_s3: "enabled" or "disabled", default: "disabled"
- nextcloud_s3_host
- nextcloud_s3_bucket
- nextcloud_s3_key
- nextcloud_s3_secret
- nextcloud_s3_port (default 443)
- nextcloud_s3_ssl (default true)
- nextcloud_s3_region (mandatory if the bucket is created outside of Nextcloud, otherwise it will default to a random region)
- nextcloud_s3_usepath_style (default false)
- nextcloud_smtp: "enabled" or "disabled", default: "disabled"
- nextcloud_smtp_server: "smtp.sendgrid.net"
- nextcloud_smtp_port
- nextcloud_smtp_username
- nextcloud_smtp_password
- nextcloud_smtp_from_email (just the part before the `@domain.org`)
- nextcloud_smtp_from_domain (just the domain)
- nextcloud_default_user_name: nextcloud
- nextcloud_default_group_name: nextcloud
- nextcloud_default_user_id: 3001
- nextcloud_default_group_id: 3001