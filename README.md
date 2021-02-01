# MediaWiki Services
A repository for storing a freely editable YAML input file for MediaWiki services on Miraheze servers

# Adding new Miraheze wikis
Normally, a bot will automatically update the YAML file as needed. In the event of the bot failing follow the steps below:

### Manually updating YAML
#### Adding new Miraheze subdomains
In the YAML file, add a new line (in alphabetical order) of the subdomain with the value of true.

So for the wiki https://example.miraheze.org/:
```
example: true
```

#### Adding new custom domains
In the YAML file, add a new line (in alphabetical order) of the subdomain with the value of the custom domain.

For the wiki https://example.org/ with original subdomain https://example.miraheze.org/:
```
example: 'example.org'
```
