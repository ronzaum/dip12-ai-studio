# Sources: Ursula K. Le Guin

Raw material for the unit card `expertise/unit/ursula-k-le-guin.md`. All fetched 2026-10-12. `fetch.py` = stdlib HTML-to-text script. Her site is run by the Ursula K. Le Guin Foundation.

## 1983-a-left-handed-commencement-address-mills-college.txt
- "A Left-Handed Commencement Address", speech at Mills College, 1983. Full text. Her notice on the page: "this talk is not under copyright, and may be quoted or reprinted as a whole without obtaining permission".
- URL: https://www.ursulakleguin.com/lefthand-mills-college
- How: `python3 -I fetch.py <url> out.txt`; site navigation stripped.

## 2014-national-book-foundation-medal-speech.txt
- Speech in acceptance of the National Book Foundation Medal for Distinguished Contribution to American Letters, 19 November 2014. Full text. Page notice: may be quoted without permission.
- URL: https://www.ursulakleguin.com/nbf-medal
- How: fetch.py; navigation and her two later notes stripped.

## 1986-carrier-bag-theory-of-fiction-official-book-page.txt
- Book page for *The Carrier Bag Theory of Fiction* on her site: publisher description (Ignota 2019; Cosmogenesis 2024), which quotes one line of the 1986 essay. Not the essay.
- URL: https://www.ursulakleguin.com/the-carrier-bag-theory-of-fiction
- How: fetch.py.

## 2017-library-of-america-interview-pure-imagining.txt
- "'Pure imagining,' within limits: Ursula K. Le Guin on The Hainish Novels & Stories", Library of America email Q&A with Le Guin, 2017 (page dated 5 March 2019). Full interview.
- URL: https://www.loa.org/news-and-views/1327-pure-imagining-within-limits-ursula-k-le-guin-on-the-hainish-novels-amp-stories/
- How: fetch.py.

## 2017-hainish-novels-vol-1-penguinrandomhouse-page.txt
- Publisher listing for *Hainish Novels and Stories Vol. 1* (Library of America #296, 5 September 2017, ISBN 9781598535389) on PenguinRandomHouse.com, LOA's distributor. Contains *The Left Hand of Darkness* and *The Dispossessed*.
- URL: https://www.penguinrandomhouse.com/books/555760/ursula-k-le-guin-hainish-novels-and-stories-vol-1-by-le-guin-ursula-k
- How: fetch.py; listing block only.

## 1969-left-hand-of-darkness-openlibrary-record.txt, 1974-the-dispossessed-openlibrary-record.txt, 1985-always-coming-home-openlibrary-record.txt, 2019-carrier-bag-theory-ignota-openlibrary-record.txt
- Open Library edition records: *The Left Hand of Darkness* (Ace, 1969), *The Dispossessed: An Ambiguous Utopia* (Harper & Row, 1974), *Always Coming Home* (Harper & Row, 1985), *The Carrier Bag Theory of Fiction* (Ignota, 2019, intro Donna Haraway, ISBN 9781999675998).
- URLs: https://openlibrary.org/books/OL23242517M ; https://openlibrary.org/books/OL18217873M ; https://openlibrary.org/books/OL3020726M ; https://openlibrary.org/books/OL29465029M
- How: `curl -sL https://openlibrary.org/books/<id>.json`, fields copied.

## 2026-ukl-foundation-getting-in-touch.txt
- "Getting in Touch" page on her site: headings, the Curtis Brown permissions link, and the Foundation's address and email from the page HTML.
- URL: https://www.ursulakleguin.com/getting-in-touch
- How: fetch.py for the visible text; `curl` on the HTML for the links.

## Checks
- "We'll need writers who can remember freedom — poets, visionaries — realists of a larger reality." — 2014-national-book-foundation-medal-speech.txt: line 7.
- "We live in capitalism, its power seems inescapable — but then, so did the divine right of kings. Any human power can be resisted and changed by human beings. Resistance and change often begin in art." — same file: line 10.
- "Our roots are in the dark; the earth is our country. Why did we look up for blessing — instead of around, and down?" — 1983-a-left-handed-commencement-address-mills-college.txt: line 16.
- "I hope you live without the need to dominate, and without the need to be dominated." — same file: line 16.
- "the dark that nourishes", "where the future is" — same file: line 16.
- "before the tool that forces energy outward, we made the tool that brings energy home." — 1986-carrier-bag-theory-of-fiction-official-book-page.txt: line 7 (as quoted in the publisher description on her site; not checked against the essay itself).
- "the home, the shrine, the place that contains whatever is sacred" — same file: line 8 (publisher description, not Le Guin's sentence; the card says so).
- "and I had to plan out the trek across the Gobrin Ice just as carefully as Estraven did, ounce by ounce and day by day." — 2017-library-of-america-interview-pure-imagining.txt: line 20.
- "more like a forest than a tree" — same file: line 11.
- "Science fiction imagines other places, other times, other beings and ways of being, by using the tools of realism and working almost entirely within its limits." — same file: line 15.
- Works: HarperCollins and Ignota pages could not be fetched (403 / 500), so the links are Open Library records plus the Penguin Random House listing for the Library of America volume. Publisher and year for each first edition are as given in those records.
- On the lead note "Bryn Mawr commencement": her site lists the 1983 Mills College address ("A Left-Handed Commencement Address"); it does not host a Bryn Mawr text, so none is cited. The 1986 Bryn Mawr commencement address is in *Dancing at the Edge of the World* (1989); not fetched.
- Contact route re-checked 2026-10-12: the "Rights to publish or reprint text" button on the Getting in Touch page still goes to https://curtisbrown.com/permissions/; the page HTML also carries a button to https://gingerclarkliterary.com/Permissions (Ginger Clark Literary) in another block, so either agency may answer. Open Library was unreachable (connection refused) during the review; the records above were fetched earlier the same day.
- Not confirmed / not saved: no authorised free full text of "The Carrier Bag Theory of Fiction" was found (The Anarchist Library page returned 404; Wayback rate-limited). The Paris Review interview (paywalled in part) is not linked or quoted.
