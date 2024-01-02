
# micro-maria
MariaDB Docker container builder.

# How to Apply
1. Create a `.env` file with the following content:

```bash
NFS_DIR=$your_nfs_dir
OUTER_PORT=$external_port
MYSQL_ROOT_PASSWORD=$root_password
MYSQL_DATABASE=$database_name
MYSQL_USER=$user_name
MYSQL_PASSWORD=$user_password
MYSQL_TCP_PORT=$inner_port
MYSQL_ROOT_HOST=%
```

3. Execute `deploy.sh`.

```bash
bash deploy.sh
```

