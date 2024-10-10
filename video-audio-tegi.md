`<video>` - veb-sahifada video ko‘rsatish uchun ishlatiladi. Bu element turli formatdagi videolarni qo'llab-quvvatlaydi va unga turli atributlar qo'shish orqali video ijrosini boshqarish mumkin

Example:

```html
<video src="kino.mp4"></video>
```

## `video` tegining asosiy attributlari/elementlari:

- **controls** - Video boshqarish uchun ijro boshqaruvlarini ko‘rsatadi (play, pause va boshqalar).
- **autoplay** - Videoni avtomatik ravishda ijro qiladi. Foydalanuvchi sahifani ochganda video avtomatik boshlanadi. Biroq, ba'zi brauzerlar avto-ijroni ovozsiz qilishni talab qiladi.
- **loop** - Videoni tugaganidan keyin qayta ijro qiladi, ya’ni videoni cheksiz aylantiradi.
- **muted** - Videoni ovozsiz qilib qo'yadi.
- **poster** - Video ijro qilinmaguncha ko'rsatiladigan surat. Bu video yuklanishidan oldin foydalanuvchiga ko‘rinadigan "preview" rasm sifatida xizmat qiladi.
- **width** va **height** - Video o‘lchamlarini belgilaydi.

`<source>` elementi - Bu element video uchun bir nechta formatlarni taqdim etish uchun ishlatiladi. Bu orqali brauzer qaysi formatni qo‘llab-quvvatlashiga qarab, to‘g‘ri formatni tanlaydi.

Example:

```html
<video controls>
  <source src="movie.mp4" type="video/mp4" />
  <source src="movie.webm" type="video/webm" />
  Sizning brauzeringiz videoni qo‘llab-quvvatlamaydi.
</video>
```

Yuqoridagi misolda ikki turli formatdagi video fayllar kiritilgan: MP4 va WebM. Brauzer qaysi formatni qo‘llab-quvvatlasa, o‘sha formatdagi videoni o‘ynatadi.

---

`<audio>` - veb-sahifalarda ovozli fayllarni ijro etish uchun ishlatiladi. (Video tegida ishlatiladigan barcha attributlar bu tegda ham ishlaydi)

Example:

```html
<audio controls>
  <source src="audio.mp3" type="audio/mp3" />
  Sizning brauzeringiz audiolarni qo‘llab-quvvatlamaydi.
</audio>
```
