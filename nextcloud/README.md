# Nextcloud Role

## Config Vars

- hostname
- users

- nextcloud_db_docker_image
- nextcloud_default_group_id: 3001
- nextcloud_default_group_name: nextcloud
- nextcloud_default_user_id: 3001
- nextcloud_default_user_name: nextcloud
- nextcloud_docker_image_tag
- nextcloud_domain
- nextcloud_https: "enabled" or "disabled"
- nextcloud_install_dir
- nextcloud_main_storage_s3: "enabled" or "disabled"
- nextcloud_postgres_db
- nextcloud_postgres_password
- nextcloud_postgres_user
- nextcloud_redis_password
- nextcloud_s3_bucket
- nextcloud_s3_host
- nextcloud_s3_key
- nextcloud_s3_port
- nextcloud_s3_region (mandatory if the bucket is created outside of Nextcloud, otherwise it will default to a random region)
- nextcloud_s3_secret
- nextcloud_s3_ssl
- nextcloud_s3_usepath_style
- nextcloud_smtp: "enabled" or "disabled"
- nextcloud_smtp_from_domain (just the domain)
- nextcloud_smtp_from_email (just the part before the `@domain.org`)
- nextcloud_smtp_password
- nextcloud_smtp_port
- nextcloud_smtp_server: "smtp.sendgrid.net"
- nextcloud_smtp_username
- nextcloud_wal_g_aws_access_key_id
- nextcloud_wal_g_aws_secret_access_key
- nextcloud_wal_g_s3_prefix