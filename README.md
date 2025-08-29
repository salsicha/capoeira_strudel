# capoeira_strudel
Strudel repo for capoeira music

![Rhythms](https://github.com/salsicha/capoeira_strudel/blob/main/rhythms.jpg?raw=true)
![Rhythms](https://github.com/salsicha/capoeira_strudel/blob/main/rhythms_key.jpg?raw=true)

Capoeira Angola example:

``` strudel
samples('https://raw.githubusercontent.com/salsicha/capoeira_strudel/main/strudel.json')
s('berim:26*2 berim_caxi:7 caxi:2')
```

```
samples({
hits: [‘hits/Berimbau_Perc_01.wav’, ‘hits/Berimbau_Perc_02.wav’],
}, ‘https://raw.githubusercontent.com/salsicha/capoeira_strudel/main/‘);

s(“hits:0”)
```

Rhythm source:
https://paulista.kyiv.ua/en/rhytm-berinbau/


