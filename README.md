# APT Layout

This is an alternate keyboard layout initially based on the work done in [MTGAP][1] and [CTGAP][2] [[notes](#notes)].

There are two variations which primarily differ in where the punctuation is.


## Symmetric

This layout is intended for use on matrix/ortholinear keyboards, with punctuation in the center columns for balanced finger usage.

```txt
w c d l ' / y o u q
r s t h k p n e i a
v b g m , . f j x z
```

### ModDH

[SteveP's ModDH Analyzer](https://colemakmods.github.io/mod-dh/analyze.html) in Matrix Simple mode. I chose to omit
the SFB calculation as this analyzer seems to punish this punctuation more than others.
![ModDH Analyzer](ModDH.png)

### KLA

[KLA Analyzer](https://klanext.keyboard-design.com) using the Test corpus and the KLA JSON files included in this repo.
![KLA Analyzer](KLA.png)

---
## Traditional

This variation has a more traditional punctuation layout.

```txt
w c d l v j y o u /
r s t h k p n e i a
q b g m x z f ' , .
```
### ModDH

[SteveP's ModDH Analyzer](https://colemakmods.github.io/mod-dh/analyze.html) in Matrix Simple mode.
![ModDH Analyzer](ModDH%20Traditional.png)

---
## Notes

The CTGAP repo was taken offline. Layout for posterity is as follows:
```txt
w c l d k  j y o u /
r s t h m  p n e i a
z v g f b  q x ' , .
```

[1]: https://mathematicalmulticore.wordpress.com/the-keyboard-layout-project/
[2]: https://github.com/CTGAP/ctgap-keyboard-layout
