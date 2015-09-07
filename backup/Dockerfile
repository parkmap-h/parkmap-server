FROM docker

COPY backup.sh .
CMD sh -c "echo '* 2 * * * sh /backup.sh' | crontab - && crond -f"
