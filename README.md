# steamid-converter

## SteamIDConverter.js

### by Horse M.D.

### Make as npm by Dragolelele

```bash
npm i steamidconverter
```

```js
const SteamIDConverter = require("steamidconverter");
```

```js
SteamIDConverter.toSteamID("76561198148292752");
output: "STEAM_0:0:94013512";
```

```js
SteamIDConverter.toSteamID3("76561198148292752");
output: "U:1:188027024";
```

```js
SteamIDConverter.fromSteamID3("U:1:188027024");
output: "STEAM_0:0:94013512";
```

```js
SteamIDConverter.isSteamID("76561198148292752");
output: false;
SteamIDConverter.isSteamID("STEAM_0:0:94013512");
output: true;
```

```js
SteamIDConverter.isSteamID64("76561198148292752");
output: true;
SteamIDConverter.isSteamID64("STEAM_0:0:94013512");
output: false;
```

```js
SteamIDConverter.isSteamID3("76561198148292752");
output: false;
SteamIDConverter.isSteamID3("U:1:188027024");
output: true;
```

```js
SteamIDConverter.profileURL("76561198148292752");
output: "http://steamcommunity.com/profiles/76561198148292752";
```
