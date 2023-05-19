
# gunicorn service
    sudo vi /etc/systemd/system/gunicorn.service

# gunicorn socket
    sudo vi /etc/systemd/system/gunicorn.socket

# gunicorn 확인
    sudo systemctl start gunicorn
    sudo systemctl enable gunicorn
    sudo systemctl status gunicorn.service

# nginx
    sudo vi /etc/nginx/sites-enabled/프로젝트 이름 (여기서는 session)

# Nginx 확인
    service nginx restart
    service nginx status
