
# Bulk file-folder permission update
`find /var/www -type d -exec chmod 2775 {} \;`
`find /var/www -type f -exec chmod 0664 {} \;`
