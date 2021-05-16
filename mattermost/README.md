# Mattermost Role

## Config Vars

- mattermost_app_docker_image_tag
- mattermost_db_docker_image_tag
- mattermost_domain
- mattermost_https: "enabled" or "disabled", default: "disabled"
- mattermost_postgres_user
- mattermost_postgres_password
- mattermost_postgres_db
- mattermost_smtp: "enabled" or "disabled", default: "disabled"
- mattermost_smtp_server
- mattermost_smtp_port
- mattermost_smtp_username
- mattermost_smtp_password
- mattermost_smtp_from_name
- mattermost_smtp_from_email
- mattermost_smtp_reply_to_email
- mattermost_object_storage: "enabled" or "disabled", default: "disabled"
- mattermost_object_storage_endpoint (do not include "http://" or "https://", and don't include bucket name)
- mattermost_object_storage_access_key_id
- mattermost_object_storage_secret_access_key
- mattermost_object_storage_bucket
- mattermost_object_storage_path_prefix
- mattermost_object_storage_region
- mattermost_wal_g_aws_access_key_id
- mattermost_wal_g_aws_secret_access_key
- mattermost_wal_g_s3_prefix