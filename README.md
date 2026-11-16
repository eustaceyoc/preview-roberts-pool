# Robert's Pool Service: sample site

A one-page sample site I put together for Robert's Pool Service (Lewisville, TX). It's a concept, not their official website, and it says so at the top of the page and in the footer.

Live preview: https://preview-roberts-pool.vercel.app

The request form doesn't send anything to a server. It just opens your own email app with a message addressed to rps@robertspoolservice.com, and the phone buttons dial (972) 436-0360. There's no tracking or analytics, and the fonts are self-hosted.

## What's on the page

Only details from Robert's Pool Service's own website and public listings: business name, Lewisville, phone, email and the S Railroad St address from its Google listing (its own site was down when I checked). The service list is a placeholder to be confirmed. Anything I couldn't confirm is left out or marked to be confirmed. There are no reviews, ratings, prices, years in business or team photos.

## Photos

Stock photos from Pexels, used under the Pexels License (https://www.pexels.com/license/). They're there for mood. None of them shows Robert's Pool Service, its people or its work.

- `brick-house-pool.jpg`: "Brown and White Concrete House Near Swimming Pool" by Max Vakhtbovych on Pexels (https://www.pexels.com/photo/brown-and-white-concrete-house-near-swimming-pool-7587480/)
- `deck-pool.jpg`: "Swimming Pool Surrounded with Wooden Deck" by Engin Akyurt on Pexels (https://www.pexels.com/photo/swimming-pool-surrounded-with-wooden-deck-4177666/)

Fonts: Libre Baskerville, Karla (Google Fonts, SIL Open Font License). Full details are in `assets/provenance.json`.

## Indexing

The page has `noindex, nofollow` in a meta tag and in the `X-Robots-Tag` header (`vercel.json`), and `robots.txt` disallows everything, so it shouldn't turn up in search.

Eustace Crentsil
