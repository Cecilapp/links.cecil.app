# App template

GitHub template for a new App website.

## Development

### Install

```bash
composer install
npm install
curl -LO https://cecil.app/cecil.phar
```

### Build

```bash
npx tailwindcss -i ./themes/applanding/tailwind.css -o ./assets/styles.css --watch
php cecil.phar serve -v
```
