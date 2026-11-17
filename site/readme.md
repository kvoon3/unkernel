# x18n playground

A minimal unkernel site for the x18n.nvim demo. It imports the `unkernel`
npm SDK, boots the bundled Alpine kernel, pushes four tarballs, and runs
Neovim on a pty in xterm.js.

## Run

```sh
npm install
npm run dev
```

`npm run dev` rebuilds the asset tarballs first. It reads the plugin files
from `../../x18n.nvim` and the three install tarballs from
`../../x18n.nvim/demo/unkernel/build/page/public`. Set `X18N_NVIM` and
`DEMO_ASSETS` to override those paths.

## Deploy

```sh
npm run deploy
```

The Worker is `x18n-nvim-play` in `void.config.ts`.

## License

MIT
