replcace the code in customeskinloader.json with following one

{
  "version": "14.27",
  "buildNumber": 37,
  "loadlist": [
    {
      "name": "LocalSkin",
      "type": "Legacy",
      "checkPNG": false,
      "skin": "https://raw.github.com/Astro-diadia/skins/main/{USERNAME}.png",
      "model": "auto",
      "cape": "https://raw.githubusercontent.com/Astro-diadia/skins/main/{USERNAME}_cape.png",
      "elytra": "https://raw.githubusercontent.com/Astro-diadia/skins/main/{USERNAME}_elytra.png"
    }
  ],
  "enableDynamicSkull": true,
  "enableTransparentSkin": true,
  "forceLoadAllTextures": true,
  "enableCape": true,
  "threadPoolSize": 8,
  "enableLogStdOut": false,
  "cacheExpiry": 30,
  "forceUpdateSkull": false,
  "enableLocalProfileCache": false,
  "enableCacheAutoClean": false,
  "forceDisableCache": false
}
