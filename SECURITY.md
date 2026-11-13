# Guvenlik / Security

## Ne iceriyor? / What is here

Bu depo yalnizca **Beko Plan Optimizer kurulum paketini** ve uygulamanin guncelleme bildirimini (`update-manifest.json`) icerir. Kaynak kod, plan verisi ve kullanici bilgisi icermez.

This repository contains only the **installer** and the app's update announcement (`update-manifest.json`). It has no source code, plan data or user information.

## Butunluk dogrulamasi / Integrity check

Kurulum paketinin SHA-256 degeri README'de ve `update-manifest.json` icinde yayinlanir. Calistirmadan once `Get-FileHash` ile karsilastirin. Paket su an dijital olarak imzali degildir.

The installer's SHA-256 is published in the README and in `update-manifest.json`. Compare it with `Get-FileHash` before running. The package is currently not digitally signed.

## Bir sorunu bildirme / Reporting a problem

Guvenlik ile ilgili bir bulguyu herkese acik bir konu (issue) olarak **paylasmayin**. Bunun yerine bu deponun **Security** sekmesinden [**Report a vulnerability**](https://github.com/enzoo808/beko-chassis-plan-optimizer-releases/security/advisories/new) ile ozel bildirim gonderin. Bildirimde sirkete ait veri, personel numarasi, ekran goruntusu veya plan dosyasi paylasmayin.

Please do **not** post a security finding as a public issue. Instead, use **Report a vulnerability** on this repository's [Security tab](https://github.com/enzoo808/beko-chassis-plan-optimizer-releases/security/advisories/new) to send a private report. Do not include company data, employee numbers, screenshots or plan files in the report.
