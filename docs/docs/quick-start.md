---
title: Богино заавар
---

Энэхүү товчхон заавар нь дунд болон түүнээс ахисан туршлагатай хѳгжүүлэгчдэд зориулсан. Анхан шатнаас нь үзэх бол [манай заавар хэсгээс үзнэ үү](/tutorial/)!

## Gatsby команд мѳрийн хэрэгсэл ашиглах

<EggheadEmbed
  lessonLink="https://egghead.io/lessons/gatsby-quick-start-with-gatsby-create-develop-and-build-gatsby-sites-from-the-command-line"
  lessonTitle="Quick Start with Gatsby: Create, Develop, and Build Gatsby Sites From the Command Line"
/>

**Тэмдэглэл**: энэ бичлэг нь суулгахгүйгээр npm пакеж ашигладаг `npx` гэх багаж ашиглаж байгаа. `npx gatsby new` гэж ажиллуулах нь, компьютер дээрээ gatsby-cli суулгаад `gatsby new` гэж ажиллуулсантай адил юм.

### Gatsby команд мѳрийн хэрэгсэл суулгах нь

```shell
npm install -g gatsby-cli
```

### Шинэ веб сайт үүсгэх.

```shell
gatsby new gatsby-site
```

### Үүсгэсэн сайтын хавтасруу шилжинэ.

```shell
cd gatsby-site
```

### Хѳгжүүлэлтийн сервер асаах.

```shell
gatsby develop
```

Gatsby тохиргоогүйгээр `localhost:8000` дээр хандах боломжтой, ѳѳрчлѳлтийг шууд харуулах хѳгжүүлэлтийн орчин ажиллуулдаг.

`src/pages` доторх JavaScript хуудсуудыг засварлаад, хадгалах үед, ѳѳрчлѳлт нь хѳтѳчийг дахин дууддаг.

### Продакшн бэлэн болгох

```shell
gatsby build
```

Gatsby route бүрт JavaScript код бүхий статик HTML хуудсуудыг продакшнд бэлэн болгон янзалж тохируулсан сайт болгон үүсгэдэг.

### Ѳѳрийн компьютер дээр продакшн хувилбар ажиллуулах

```shell
gatsby serve
```

Gatsby тестлэх зорилгоор HTML сервер ажиллуулдаг. Ингэж шалгахын тулд заавал `gatsby build` ажилласан байх хэрэгтэйг санаарай.

### Команд мѳрийн хэрэгслийн заавруудыг харах

Дэлгэрэнгүй зааварыг харах бол terminal дээр `gatsby --help` гэж ажиллуулна.

Тодорхoй командын талаар бол, `gatsby КОМАНД НЭР --help` Жнь: `gatsby new --help`.

Gatsby команд мѳрийн хэрэгслийн талаар илүү дэлгэрэнгүйг [КМХ тухай](/docs/gatsby-cli/) хэсгээс харна уу.
