# Install cert bot ssl let'sencrypt on amz linux 2

install epel & certbot \(for nginx\)

```bash
sudo amazon-linux-extras install epel
sudo yum install certbot-nginx
```

get a free ssl cert, make sure to set your server IP point to your domain before hand.

```bash
sudo certbot --nginx -d your.domain.com
```



