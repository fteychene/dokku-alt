nginx: exec nginx -g "daemon off; error_log /dev/stdout info;"
ssh: mkdir /var/run/sshd; exec /usr/sbin/sshd -De
dokku: exec /srv/dokku-alt/start-dokku.sh
docker: rm /var/run/docker.pid; cgroups-mount; exec docker daemon
