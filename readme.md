# figlet-promises

A new modern figlet for modern times!

## Installation

For installation in node.js use npm

```bash
npm i figlet-promises
```

## Usage

```node.js
const figlet = require('figlet-promises');
const Figlet = new figlet();

let font = 'standard'; //scroll down for a list of available fonts

Figlet.loadFonts();
let txt = Figlet.write("Your Text Here",font);

console.log(txt);
```

List of available fonts - 
```
3-d,3x5,5lineoblique,acrobatic,alligator,alligator2,alphabet,avatar,banner,banner3-D,banner3,banner4,barbwire,basic,bell,big,bigchief,binary,block,bubble,bulbhead,calgphy2,caligraphy,catwalk,chunky,coinstak,colossal,computer,contessa,contrast,cosmic,cosmike,cricket,cursive,cyberlarge,cybermedium,cybersmall,diamond,digital,doh,doom,dotmatrix,drpepper,eftichess,eftifont,eftipiti,eftirobot,eftitalic,eftiwall,eftiwater,epic,fender,fourtops,fuzzy,goofy,gothic,graffiti,hollywood,invita,isometric1,isometric2,isometric3,isometric4,italic,ivrit,jazmine,jerusalem,katakana,kban,larry3d,lcd,lean,letters,linux,lockergnome,madrid,marquee,maxfour,mike,mini,mirror,mnemonic,morse,moscow,nancyj-fancy,nancyj-underlined,nancyj,nipples,ntgreek,o8,ogre,pawp,peaks,pebbles,pepper,poison,puffy,pyramid,relief,relief2,rev,roman,rot13,rounded,rowancap,rozzo,runic,runyc,sblood,script,serifcap,shadow,short,slant,slide,slscript,small,smisome1,smkeyboard,smscript,smshadow,smslant,smtengwar,speed,stampatello,standard,starwars,stellar,stop,straight,tanja,tengwar,term,thick,thin,threepoint,ticks,ticksslant,tinker-toy,tombstone,trek,tsalagi,twopoint,univers,usaflag,wavy,weird
```

You can also add your own figlet fonts in `.flf` format!
