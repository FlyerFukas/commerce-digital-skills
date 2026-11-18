# Commerce Digital: davranış psikolojisi skill'leri

Beş davranış psikolojisi kitabını, dijital ürün kararlarında kullanılan altı Claude skill'ine çeviren kütüphane. Dönüşüm, fiyatlandırma, onboarding, bildirim, iptal akışı ya da elde tutma sorusu geldiğinde Claude'u doğru kitaba yönlendirir, desenleri ve etik sınırları birlikte uygular.

*Six Claude skills that turn five behavioural-psychology books into product guidance: conversion, pricing, onboarding, notifications, cancellation flows and retention, with an ethics and dark-pattern check built in.*

| Skill | Kaynak kitap | Ne için |
|---|---|---|
| `commerce-digital` | (yönlendirici) | Soruyu teşhis eder, doğru kitaba ya da birkaçına gönderir, ortak etik ve yasal çerçeveyi uygular |
| `commerce-digital-hooked` | Nir Eyal, *Hooked* | Tetikleyici, eylem, değişken ödül, yatırım: alışkanlık döngüsü |
| `commerce-digital-cialdini` | Robert Cialdini, *Influence* | Karşılıklılık, tutarlılık, sosyal kanıt, otorite, kıtlık |
| `commerce-digital-kahneman` | Daniel Kahneman, *Thinking, Fast and Slow* | İki sistem, çapa, kayıptan kaçınma, çerçeveleme |
| `commerce-digital-ariely` | Dan Ariely, *Predictably Irrational* | Tuzak seçenek, BEDAVA etkisi, sosyal ve piyasa normları |
| `commerce-digital-sutherland` | Rory Sutherland, *Alchemy* | Mantıksız ama işe yarayan çözümler, algının değeri |

Her kitap skill'inde `SKILL.md` (ne zaman, nasıl), `patterns.md` (ürün desenleri), `glossary.md` (terimler) ve çoğunda `cheatsheet.md` var.

## Bu açık kopyada olmayanlar

- **Bölüm bölüm kitap özetleri** (`chapters/`) telif nedeniyle yok. `SKILL.md` içindeki `ch01` gibi işaretler o özetlere gider; açık kopyada yalnız bölüm adı kalır.
- **Kitaplardan uzun alıntılar** çıkarıldı, yerlerinde not var.
- Sutherland skill'i kitabın yalnız giriş bölümüne dayanır; bunu kendi dosyalarında da yazar.

Kitapların kendisi bu depoda değildir; okumak için satın alın.

## Kurulum

```bash
git clone https://github.com/FlyerFukas/commerce-digital-skills
cp -r commerce-digital-skills/skills/* ~/.claude/skills/
```

Claude Code yeniden açılınca skill'ler listede görünür. Giriş noktası `commerce-digital`.

## Lisans

Bu depodaki özgün metin kişisel, eğitim ve kâr amacı gütmeyen kullanım için ücretsizdir (PolyForm Noncommercial 1.0.0). Kitaplardaki fikirler ve terimler yazarlarına aittir.
