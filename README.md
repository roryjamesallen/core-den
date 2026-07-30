# core den website
- 'Live' site files all go inside `public_html`
- Other gubbins can go above `public_html` (in the same place as this file, `README.md`), they'll be private so not accessible by site visitors
- Make pages (inside `public_html`) called something like `mypage.html` and then you can go to `https://den.hogwild.uk/mypage`
- You can link to other pages using 'relative links' e.g. index.html can have a link like `<a href=rory.html>` instead of the whole `<a href=https://den.hogwild.uk/rory>`. This also means it'll work if you test it out locally using XAMPP or something because it will use the file on your computer instead of redirecting to the live page.
