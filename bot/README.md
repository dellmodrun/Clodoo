# @dellmodrun/clodoo-bot

The autonomous AI builder behind **[Clodoo](https://github.com/dellmodrun/Clodoo)** — it
designs and builds an entire city on a live Minecraft world, block by block, 24/7.

```bash
npm install
cp ai.config.example.json ai.config.json   # your OpenAI-compatible endpoint + key
npm start
```

Needs a Paper Minecraft server (RCON + the dynmap plugin). Streams a live cam on `:3007`,
serves live data + a cam frame on `:8890`, and writes `clodoo-live.json` for the site dashboard.

Site: <https://woodcutleaf.com> · MIT License.
