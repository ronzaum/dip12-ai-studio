# Sources: Caleb Femi

Raw material for `expertise/unit/caleb-femi.md`. All fetched 2026-10-12. No poems are saved or quoted; interviews and talks only.

## 2020-i-see-myself-as-an-archivist-penguin-interview.txt
- Title: "Caleb Femi: 'I see myself as an archivist'". Interview feature, Penguin.co.uk, November 2020 (around publication of Poor, 4/5 Nov 2020).
- URL: https://www.penguin.co.uk/discover/articles/caleb-femi-poor-interview (the original /articles/2020/11/ URL redirects here; link updated on review 2026-10-12)
- How obtained: `python3 -I "$T/fetch.py" "<url>" penguin-interview.txt`
- Saved: the full article (~740 words).

## 2020-complex-interview-imagination.txt
- Title: "'In Any Circumstance, Humans Need Imagination In Order To Survive': An Interview With Caleb Femi". By Robert Kazandjian, Complex, 19 Nov 2020.
- URL: https://au.complex.com/pop-culture/a/robert-kazandjian/caleb-femi-interview
- How obtained: `python3 -I "$T/fetch.py" "<url>" complex.txt`; site chrome after "Trending" trimmed.
- Saved: the full interview (freely published; ~5,300 words).

## 2017-roadman-or-man-on-the-road-tedxpeckham.txt
- Title: "Roadman or Man on the Road | Caleb Femi | TEDxPeckham". YouTube, TEDx Talks channel, uploaded 1 Aug 2017, 16 min.
- URL: https://www.youtube.com/watch?v=7vKUeYcdYM8
- How obtained: `"$V/yt-dlp" --skip-download --write-auto-sub --write-sub --sub-lang en --sub-format vtt -o 7vKUeYcdYM8 "<url>"` then `python3 -I "$T/vtt2txt.py" 7vKUeYcdYM8.en.vtt 7vKUeYcdYM8.txt`
- Saved: full caption transcript with [HH:MM:SS] timestamps.

## 2025-the-wickedest-library-science-interview.txt
- Title: "The Wickedest by Caleb Femi". Library Science book-club interview, YouTube, uploaded 9 Feb 2025, 21 min. Auto-captions: names and some words are garbled ("Caleb FEI", "the wickedness").
- URL: https://www.youtube.com/watch?v=D341zmoOuUE
- How obtained: same yt-dlp + vtt2txt.py commands with id D341zmoOuUE.
- Saved: full caption transcript with timestamps.

## 2025-the-wickedest-publisher-description-macmillan.txt
- Title: The Wickedest, US publisher page (MCD / Farrar, Straus and Giroux): genre, on-sale date, description, imprint, ISBN. Not Femi's voice; saved so the blurb quoted in the card's Ritual hook is checkable.
- URL: https://us.macmillan.com/books/9780374616625/thewickedest/
- How obtained: `python3 -I "$T/fetch.py" "<url>" wickedest-us.txt`, then the book-details block only (37 lines) saved with `sed -n 388,424p`.

## Pages fetched for Works and Contact (not saved as text)
- Poor, Penguin: https://www.penguin.co.uk/books/314754/poor-by-femi-caleb/9780141992150 (Imprint: Penguin, Published 05/11/2020, ISBN 9780141992150, 160 pages).
- The Wickedest, HarperCollins UK: https://www.harpercollins.co.uk/products/the-wickedest-caleb-femi (fetched; page title "The Wickedest by Caleb Femi – HarperCollins Publishers UK"; the edition fields are unrendered template placeholders, so no UK date or ISBN is visible in the fetched text). Review 2026-10-12: the same page's product data (`/products/the-wickedest-caleb-femi.js`) gives vendor "Fourth Estate", Hardback ISBN 9780008688240 (£14.99), ebook 9780008688233, audiobook 9780008688226. Hardback publication date 12/09/2024 from Mr B's Emporium (https://mrbsemporium.com/shop/books/the-wickedest/, publisher "HarperCollins Publishers"); Jaffe & Neale (http://www.jaffeandneale.co.uk/product/the-wickedest) gives Publisher 4th Estate, Hardback, 96 pages, same ISBN. Open Library and WorldCat were unreachable or blocked that day.
- The Wickedest, US: https://us.macmillan.com/books/9780374616625/thewickedest/ (Imprint MCD, On Sale 01/21/2025, ISBN 9780374616625; blurb quoted on the card).
- 4th Estate audiobook page https://www.4thestate.co.uk/products/the-wickedest-caleb-femi (read via WebFetch only: "4th Estate, an imprint of HarperCollins Publishers Ltd", ISBN 978-0-00-868822-6, audiobook).
- AA event page https://new.aaschool.ac.uk/public/whats-on/in-conversation-caleb-femi-kazeem-kuteyi: fetch failed (expired TLS certificate); link only. Review 2026-10-12: still unreachable (404 with certificate check off; aaschool.ac.uk and aa.linkedbyair.net mirrors return 403/429 to automated fetch).
- us.macmillan.com pages (book and author) returned 403 to curl and WebFetch on the review re-check 2026-10-12 (bot block); the blurb was fetched and saved earlier the same day.
- calebfemi.com: fetched, 19 words of script boilerplate; the site exists but renders in-browser only.

## Checks
Each card quote, the file, and the line where it appears (line numbers include the 4 header lines). Transcript quotes run across caption lines; the fragment grepped is on the first line given.
- "Everything is structurally against working-class people. I'm writing how they exist in spite of that." → `2020-i-see-myself-as-an-archivist-penguin-interview.txt` line 29 (pull-quote in the article; the longer version of the same point is at line 35)
- "And the state of the space in which you live tells you how much you’re worth. It tells you how the world sees you, and you start to digest and internalise that." → `2020-complex-interview-imagination.txt` line 129
- "That’s the only bit of imagination I wanted to police, by injecting images to counterbalance the images people see on the news of distressed Black people." → `2020-complex-interview-imagination.txt` line 145
- "But the thing about being on the roads is that it was essentially a proverbial safe space for us to come together under a common struggle." → `2017-roadman-or-man-on-the-road-tedxpeckham.txt` lines 177–181, [00:07:04]–[00:07:11]
- "the precious time that we have together on this Earth to celebrate one another is Paramount" → `2025-the-wickedest-library-science-interview.txt` lines 338–340, [00:14:22]–[00:14:28]
- How they work: "documents the lives and times of people who live in my imagination, both in reality and in fantasy" → Penguin file line 37; "can't necessarily be contained in iambic pentameter" → line 43; "a good party is so multifaceted" → 2025 file lines 229–230 [00:09:37]; "they all try to capture a perspective" → lines 257–258 [00:10:45]–[00:10:49]; Virgil Abloh and David Mancuso → lines 57–60 [00:02:09]–[00:02:28] (auto-caption spells it "David manuso"); 11 to 4 → line 207 [00:08:49].
- Hooks: "just don't tell anyone about this" → 2025 file line 359 [00:15:25] (card timestamp corrected on review from 00:15:23); "exchange human information" → lines 73–74 [00:02:59]–[00:03:02]; "science behind a successful night" → line 208 [00:08:51] (card timestamp corrected on review from 00:08:46); "65 stories, 1,444 homes" and "need to leave the estate" → Complex file line 125; seven people in one bedroom → TEDx file lines 171–175 [00:06:46]–[00:06:56] (paraphrased on the card, not quoted); "loss of landmarks", "gated communities" → Complex file line 133; "the longest running house party in the South London shoob scene, always held at an undisclosed inner-city spot" → `2025-the-wickedest-publisher-description-macmillan.txt` line 15. Form 696 is mentioned in a Tribune review (fetched, not saved); it is background, not a quote.
- Review 2026-10-12: all quotes re-checked verbatim against the files (timestamps stripped for the caption transcripts). The phrase "secret city of flair" in the Sacred / profane hook was not in any saved file and was removed from the card. The 2025 interview quotes in the Hooks are now labelled auto-captions on the card.
- Resolved on review (card now `verified`): (1) The Wickedest UK edition: 4th Estate (HarperCollins UK), hardback 12 Sep 2024, ISBN 9780008688240, see above. (2) The AA event page is marked not reachable with the date. (3) Laureate end date still not on the card.
- Original notes: (1) The Wickedest UK edition year and imprint: the brief said "2024, Penguin"; the HarperCollins UK page I fetched carries the title but its edition fields did not render, and the 4th Estate imprint was read only through WebFetch. The US date (21 Jan 2025) is confirmed on the fetched Macmillan page. (2) The AA event page could not be fetched (expired certificate). (3) The Young People's Laureate dates: the Penguin interview confirms "In 2016 he was selected as the First Young People's Laureate for London"; the end date (2018) is not in any saved file, so the card gives 2016 only.
- Peer review 2026-10-12 (second model, findings verified by hand): (1) Positions #1 was Penguin's editorial pull-quote (file line 29), not Femi's sentence; replaced with his own words from line 33. (2) "just don't tell anyone about this" (00:15:25) is the interviewer paraphrasing the book's ending (the speaker goes on "I was reading this on set"); hook now says so. (3) "11 pm to 4 am" came from a hypothetical ("if it starts at 11 and finishes at 4", 00:08:46), cut. (4) Form 696 claim rested on an unsaved Tribune review; cut. (5) "English teacher": Complex says only "a teacher"; corrected.
