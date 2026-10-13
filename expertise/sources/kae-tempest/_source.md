# Sources: Kae Tempest

Raw material for `expertise/unit/kae-tempest.md`. All fetched 2026-10-12. No lyrics or poem text saved or quoted. *On Connection* itself is not excerpted; the Guardian essay below is Tempest's own first-person piece published to accompany it.

## 2020-what-i-have-learned-from-20-years-on-the-mic-guardian.txt
- Title: "Kae Tempest: what I have learned from 20 years on the mic". By Kae Tempest. The Guardian, 3 Oct 2020. Ends "On Connection by Kae Tempest is published by Faber & Faber."
- URL: https://www.theguardian.com/books/2020/oct/03/kae-tempest-what-i-have-learned-from-20-years-on-the-mic
- How obtained: `python3 -I "$T/fetch.py" "<url>" guardian2020.txt`; chrome after "Explore more on these topics" trimmed.
- Saved: the full essay (~1,300 words, freely published).

## 2022-boiling-hot-secret-guardian-interview.txt
- Title: "Kae Tempest: 'I was living with this boiling hot secret in my heart'". Interview by Michael Segalov. The Guardian, 12 Mar 2022.
- URL: https://www.theguardian.com/culture/2022/mar/12/kae-tempest-i-was-living-with-this-boiling-hot-secret-in-my-heart
- How obtained: `python3 -I "$T/fetch.py" "<url>" guardian2022.txt`; chrome trimmed.
- Saved: the full interview (~2,500 words, freely published).

## 2026-im-just-glad-to-be-alive-guardian-interview.txt
- Title: "Kae Tempest on creativity and his gender transition: 'I'm just glad to be alive'". Interview by Alex Needham. The Guardian, 18 Apr 2026.
- URL: https://www.theguardian.com/culture/2026/apr/18/kae-tempest-on-creativity-and-his-gender-transition-im-just-glad-to-be-alive
- How obtained: `python3 -I "$T/fetch.py" "<url>" guardian2026.txt`; chrome trimmed.
- Saved: the full interview (~2,500 words).

## 2023-divisible-by-itself-and-one-panmacmillan-interview.txt
- Title: "'Through the artifice of putting words into those rhythms and into that metre, you create a different kind of truth': Kae Tempest on their new collection". Pan Macmillan blog, 27 Apr 2023 (the URL slug mentions Let Them Eat Chaos; the page is the Divisible by Itself and One interview).
- URL: https://panmacmillan.com/blogs/literary/kae-tempest-s-let-them-eat-chaos-out-now
- How obtained: `python3 -I "$T/fetch.py" "<url>" panmac-ltec-interview.txt`
- Saved: the full interview (~1,300 words).

## 2021-kae-tempest-in-conversation-with-max-porter-mcrlitfest.txt
- Title: "Kae Tempest in conversation with Max Porter". Manchester Literature Festival, YouTube, uploaded 6 Jan 2021, 60 min. Auto-captions (lower-case, no punctuation).
- URL: https://www.youtube.com/watch?v=DJYO3wQDq_c
- How obtained: `"$V/yt-dlp" --skip-download --write-auto-sub --write-sub --sub-lang en --sub-format vtt -o DJYO3wQDq_c "<url>"` then `python3 -I "$T/vtt2txt.py" DJYO3wQDq_c.en.vtt DJYO3wQDq_c.txt`
- Saved: full caption transcript with [HH:MM:SS] timestamps.

## Pages fetched for Works and Contact (not saved as text)
- On Connection, Faber: https://www.faber.co.uk/product/9780571370436-on-connection/ (Paperback, ISBN 9780571370436, Date Published 17.03.2022; author note: "On Connection, published by Faber & Faber in 2020").
- Brand New Ancients, Pan Macmillan: https://www.panmacmillan.com/authors/kae-tempest/brand-new-ancients/9781447257684 (Imprint: Picador, 29 August 2013, 64 pages).
- Hold Your Own: https://www.panmacmillan.com/authors/kae-tempest/hold-your-own/9781447241225 (Imprint: Picador, 09 October 2014, 128 pages).
- Let Them Eat Chaos: https://www.panmacmillan.com/authors/kae-tempest/let-them-eat-chaos/9781509830008 (Imprint: Picador, 06 October 2016, 80 pages).
- Faber author page https://www.faber.co.uk/author/kae-tempest/ (fetched).
- David Higham Associates page https://davidhigham.co.uk/?p=48645: fetch.py got HTTP 403; read via WebFetch (agents Nicola Chang, Georgie Smith, Zara Petranova).

## Checks
Each card quote, the file, and the line where it appears (line numbers include the 4 header lines).
- "Words on a page are incomplete. The poem, the novel or the non-fiction pamphlet are finished when they are taken up and engaged with. Connection is collaborative." → `2020-what-i-have-learned-from-20-years-on-the-mic-guardian.txt` line 41
- "When the connection is made, everything is linked and moving towards a moment of mutual feeling, a creative connection that binds the entire room into a unified present." → same file, line 59
- "I’m always coming back to this idea of how to break cycles, or how to acknowledge and find peace with cycles." → `2023-divisible-by-itself-and-one-panmacmillan-interview.txt` line 29
- "It’s because I feel so close to this place, and the people I’ve known my whole life here." → `2022-boiling-hot-secret-guardian-interview.txt` line 36
- "When I perform I go to the depths; beyond gender, beyond body. I leave everything behind. That’s why it was addictive." → `2022-boiling-hot-secret-guardian-interview.txt` line 106
- How they work: "from the same place, rhythmically, as I would write lyrics" → 2023 file line 35; "over a period of many months, in weeklong bursts of intense creativity" and the quartet → 2020 file line 57; "three stations" → 2020 file line 47; "took about three years", residencies → 2026 file line 56; Ian Rickson, Paradise → 2026 file lines 52 and 70 (caption: "Paradise by Kae Tempest at the National Theatre, London, in 2021").
- Hooks: "i beat my chest when i'm on stage and i sway" → 2021 transcript line 1287 [00:44:29]; "we have sinned" → lines 1289–1290 [00:44:31]–[00:44:32]; "we are lost we are lost" → line 1290 [00:44:34] (speaker is Tempest, on performing Europe Is Lost); "Patterns to the language that I hadn’t been aware of when I was writing" → 2020 file line 57; "Between the day that everyone in attendance had brought into the room with them, and the prospect of the night to come" → 2020 file line 59; "the club was the place" → 2021 transcript line 201 [00:08:14]; "I don’t understand how my body, our bodies, became a territory for war" → 2022 file line 64.
- Pronouns: the 2020 and 2022 Guardian pieces and the 2023 Pan Macmillan interview use they/them; the April 2026 Guardian interview uses he/him. The card says so and uses "he" after 2026.
- Unconfirmed: nothing on the card. The David Higham page was read through WebFetch only (fetch.py returned 403); the agents' names come from that read.
- Review 2026-10-12: all 5 Positions, 2 How-they-work quotes and 7 Hook quotes re-checked verbatim; the 2021 timestamps (00:08:14, 00:44:29) match the transcript. Faber (pb 17.03.2022, "published by Faber & Faber in 2020") and the three Picador pages (2013, 2014, 2016) re-fetched and confirmed. David Higham page re-read via WebFetch (Nicola Chang agent; Georgie Smith film, TV and stage). All free-material links resolve; the Pan Macmillan blog URL now redirects to https://www.panmacmillan.com/blogs/literary/kae-tempest-on-writing. The 2021 hook citations are now labelled auto-captions on the card.
