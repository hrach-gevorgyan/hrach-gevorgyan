Two projects, one idea: your data stays on your own machine. No account, no cloud, nothing sent anywhere.

## <img src="https://offlog.io/icon-512.png" height="28" alt=""> Offlog

A task manager for Windows and Android. Board, List and Agenda views; your phone syncs with your PC over your own Wi-Fi, end-to-end encrypted. Free and open source.

<p>
  <a href="https://offlog.io"><img src="https://offlog.io/img/board-2x.webp" alt="Offlog's Board on Windows" width="72%"></a>
  <a href="https://offlog.io"><img src="https://offlog.io/img/phone-home-2x.webp" alt="Offlog's Home screen on Android" width="24%"></a>
</p>

[offlog.io](https://offlog.io) · [Source](https://github.com/hrach-gevorgyan/offlog) · [Download](https://github.com/hrach-gevorgyan/offlog/releases/latest)

## <img src="https://raw.githubusercontent.com/hrach-gevorgyan/coreval/master/man/figures/logo.png" height="32" alt=""> coreval

Check SDTM, SEND and USDM clinical trial data against CDISC's published conformance rules, without leaving R. You get the problems in plain words, pointing at the exact row and variable, in a few seconds, before the data goes to your validation tool.

The rules ship inside the package, so it works offline and your data never leaves your machine.

```r
install.packages("coreval")
result <- coreval::check_dataset(dm)
```

[CRAN](https://cran.r-project.org/package=coreval) · [Source](https://github.com/hrach-gevorgyan/coreval)

---

<sub>Also: [NyxDB](https://github.com/hrach-gevorgyan/nyxdb), the sync server behind Offlog · [maik](https://github.com/hrach-gevorgyan/maik), on-device AI chat for Android · [hashvir](https://github.com/hrach-gevorgyan/hashvir) and [puy-puy](https://github.com/hrach-gevorgyan/puy-puy), offline Armenian games for toddlers</sub>
