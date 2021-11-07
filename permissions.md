
## How to set bulk file and folder permissions ?

```sh
`find /var/www -type d -exec chmod 2775 {} \;`  
`find /var/www -type f -exec chmod 0664 {} \;`
```


