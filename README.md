# FACES — Site Concept (editable files)

## Kufungua (Open it)
Bonyeza mara mbili `index.html` — itafunguka kwenye browser yako (Chrome/Safari/Edge). Hakuna installation inayohitajika.

## Kubadilisha maudhui (Editing)
Fungua folder hii kwa Notepad, TextEdit, au bora zaidi **VS Code** (bure, download kutoka code.visualstudio.com).

- **styles.css** — rangi, fonts, spacing kwa site nzima. Badilisha hapa na kila page inabadilika.
- **index.html** — homepage
- **about.html** — About page
- **sneaker-news.html** — Sneaker News
- **blog.html** — Fashion Blog
- **marketplace.html** — Marketplace / products (orodha ya bidhaa iko chini ya page, ndani ya `<script>`, array inaitwa `PRODUCTS`)
- **payment.html** — Checkout preview (M-Pesa / Airtel Money / Card)
- **team.html** — The Face Behind FACES
- **photobooth.html** — Photobooth
- **assets/** — logos zako tatu. Weka picha nyingine (bidhaa, team, community) humu humu na uzitaje kwenye html (mfano `<img src="assets/picha-yako.jpg">`)

Bei, majina ya bidhaa, maandishi ya blog, na majina ya team ni **placeholder** — tafuta na badilisha ("Find & Replace") moja kwa moja kwenye kila faili.

## Kutoa link ambayo mtu anaweza kufungua kwa simu (Getting a phone-ready link)
Faili hizi peke yake zikiwa kwenye computer yako haziwezi kufunguliwa na simu ya mtu mwingine — ni local tu. Njia rahisi zaidi, bila GitHub:

1. Nenda **netlify.com** (au vercel.com) → account ya bure
2. "Drag and drop" folder hii nzima (faces-export) kwenye page yao
3. Unapata link ya moja kwa moja (mfano `faces-boss-preview.netlify.app`) — link hiyo inafunguka kwa simu yoyote, popote

Hiyo ndiyo njia ya haraka zaidi ya kupata "link ya kutuma kwa simu" bila kugusa code au GitHub. Ukiwa tayari kujenga site halisi (malipo ya kweli, database ya bidhaa), ndipo tutahitaji backend na hosting ya kudumu zaidi (Render/Vercel + GitHub kwa ajili ya kuhifadhi code).
