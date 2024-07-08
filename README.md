# Clemson Forge Website
## Setup
```bash
pnpm install # install necessary dependencies
pnpm run dev # run development server (or use hugo server)
```

### Other Commands
```bash
pnpm run update-theme    # update the theme to latest version
pnpm run update-modules  # update all modules
pnpm run remove-darkmode # remove dark mode from the project
pnpm run build           # build project locally
```

## Configs
- `hugo.toml`: site title, base URL, language, theme, plugins, etc.
- `config/_default/params.toml`: logo, favicon, search, SEO metadata, etc.
- `data/theme.json`: colors and fonts
- `data/social.json`: social media and other links

## License
This project is licensed under the MIT License.

## Acknowledgments
This project uses [Hugoplate from Zeon Studio](https://github.com/zeon-studio/hugoplate) as a basis. Hugoplate is licensed under the [MIT License](https://github.com/zeon-studio/hugoplate/blob/main/LICENSE) (copyright Zeon Studio 2023-present).
This project additionally uses some code from [reveal-hugo](https://github.com/joshed-io/reveal-hugo). reveal-hugo is licensed under the [MIT License](https://github.com/joshed-io/reveal-hugo/blob/master/LICENSE) (copyright 2018 Josh Dzielak).
Other attributions (as provided by Hugoplate) can be found in the respective files.
