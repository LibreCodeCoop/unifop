# Static site for UNIFOP

## Run the application

```bash
docker-compose up
```

## Compile css

Goto container bash:

```bash
docker-compose exec php7 bash
```

run this command:

```bash
vendor/bin/pscss < scss/style.scss > css/style.css
```

## Base template

TITLE: Exclusivity - Free Bootstrap 4 Template
AUTHOR: Free-Template.co
LICENSE: Under Creative Commons 3.0 (free-template.co/license)