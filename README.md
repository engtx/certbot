# certbot

# note!
vscode does not have permission to view whats inside the letsencrypt directoy so it will look empty. use a terminal to view and manage the files.

#instructions
Copy/symlink the generated certs in
/letsencrypt/live
/letsencrypt/archive
to the webserver projects letsencrypt directory is.

# Generate a cert for your website. 
```docker-compose run --rm certbot certonly --webroot -w /var/www/certbot -d cyrusbavarian.com -d www.cyrusbavarian.com```

