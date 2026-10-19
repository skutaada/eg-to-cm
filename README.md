# OPTCG Decklist Converter

Converts One Piece TCG decklists from the Egman Events or gumgum.gg export format to the Cardmarket wants list import format.

```
4 OP01-016 Nami   →   4x Nami OP01-016
4xOP01-016        →   4x Nami OP01-016
```

It's a single `index.html` file with no build step and no dependencies. When a decklist lists only card codes, the page looks up the names from the [punk-records](https://github.com/buhbbl/punk-records) card dataset on GitHub.

## Hosting on GitHub Pages

1. Push this folder to a GitHub repository.
2. Go to **Settings → Pages**, set **Source** to "Deploy from a branch", then choose `main` and `/ (root)`.
3. The site goes live at `https://<user>.github.io/<repo>/`.
