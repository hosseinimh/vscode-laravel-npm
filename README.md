# vscode-laravel-npm

This script opens two new terminals in vscode, runs `php artisan serve` in first and `npm run watch` in another, as soon as you open the code directory.

You just need to copy `tasks.json` file into `.vscode` directory.

Below is my directory structure:

```bash
├───.vscode
├───project
└───public_html
```

Laravel codes are in `project` directory, one above `public_html`.
