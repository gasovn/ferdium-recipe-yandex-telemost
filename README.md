# Ferdium recipe: Yandex Telemost

Ferdium recipe for Yandex Telemost (https://telemost.360.yandex.ru). The same web client also serves the consumer account at https://telemost.yandex.ru; add it as a second service with the custom URL option.

## Development

Link the recipe into Ferdium's development recipes folder, then restart Ferdium:

    scripts/dev-link.sh

The script handles both native and Flatpak installs. After restarting, add the service from the recipe list. For a personal account, enable "Use custom URL" and enter https://telemost.yandex.ru.

## Layout

    yandex-telemost/     the recipe, ready to copy into ferdium-recipes/recipes/
    scripts/dev-link.sh  symlink helper for local development

## License

MIT
