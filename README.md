## Windows

[WinCompose.info](https://wincompose.info/) is still the SEO-canonical home of that software,
a.k.a. [samhocevar/wincompose](https://github.com/samhocevar/wincompose),
but its latest release as of this writing is WinCompose version 0.9.11 (Sep 3, 2021):

```
PS U:\Users\okeeblow\Repos\XCompose> winget search wincompose
Name       Id                    Version Source
------------------------------------------------
WinCompose SamHocevar.WinCompose 0.9.11  winget
```

With that version on a new machine, I started experiencing
[Issue #350 — Notification area tooltip always shown](https://github.com/samhocevar/wincompose/issues/350),
which is *incredibly annoying* to say the least.

Use this fork instead: [ell1010/wincompose](https://github.com/ell1010/wincompose).
