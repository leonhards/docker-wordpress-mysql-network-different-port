Another sample create new wordpress container using different port connected to mysql via network.

docker-compose.yml is used to install WP connected to MySQL network.

docker-compose1.yml is used to install WP + MySQL (without network).

Network nginx-proxy is used for reverse proxy (http) if you want to build multiple website in docker with different port.

<b>Note:</b>
<br>First, database should be created manually before running this docker file.
<br>DB Collation: <code>utf8mb4_unicode_ci</code>
