# CompanyCam API V2 developer docs
--------

### Start development server
`bundle exec middleman serve`

### Add a new resource with

`thor generate model ClassName`

You will need
```
OAUTH_SECRET=xxx
OAUTH_ID=xxx
OAUTH_TOKEN=xxx
```

In your .env.

### Customise content of a resource

Look in the appropriate .yml file.

# Deploy

./deploy.sh
