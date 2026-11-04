# Partizip II Trainer

A small browser game for practising irregular German verbs: the infinitive and its Perfekt form with *hat* or *ist*.

**Play:** https://kulaggin.github.io/partizip-trainer/

## Modes

1. **Tippen:** type the Perfekt form (`trinken` → `hat getrunken`).
2. **hat oder ist?:** pick the auxiliary verb (keys H / I).
3. **Auswahl:** choose the correct form out of four (keys 1–4).
4. **Bedeutung:** see the German verb and choose its meaning out of four (keys 1–4). Wrong options often look alike, such as *mitbringen* and *mitnehmen*.
5. **Übersetzen:** see the meaning and type the German infinitive.

Verbs you get wrong come up more often. Progress is saved in your browser. Modes 4 and 5 keep their own progress, separate from the Perfekt modes.

## Word lists

There are two built-in lists: all 39 verbs from the course handout, and 69 prefix verbs from the course book up to page 180 (44 separable like *mitbringen*, 25 inseparable like *bezahlen*), each with its Präsens form. Add your own lists with **+ Neue Liste**, one verb per line:

```
trinken; hat getrunken; to drink
fahren; ist gefahren; to go (by vehicle)
```

On this site, custom lists are stored in your browser only.

## Languages

The interface and the built-in verb translations are available in 22 languages: German, English, Chinese, Hindi, Spanish, Arabic, French, Bengali, Portuguese, Russian, Indonesian, Urdu, Japanese, Turkish, Vietnamese, Korean, Persian, Swahili, Tagalog, Italian, Polish and Ukrainian (Arabic, Persian and Urdu right to left). The site picks your browser language; change it with the Language picker. In German the verb translations are hidden. Corrections from native speakers are welcome.

Everything is a single static `index.html`, with no build step.
