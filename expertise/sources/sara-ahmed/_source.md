# Sources: Sara Ahmed

Raw material behind `expertise/unit/sara-ahmed.md`. Fetched 2026-10-12.

## 2018-queer-use.txt
- Title: Queer Use (text of her lecture, given 2017–2018 at Queen Mary, CLAGS, Berkeley, UCL, Cambridge and elsewhere)
- Author: Sara Ahmed. Date: 8 November 2018. Where: feministkilljoys.com
- URL: https://feministkilljoys.com/2018/11/08/queer-use/
- How obtained: `python3 -I fetch.py <url> out.txt`. Saved: whole post (freely published lecture text).

## 2020-slammed-doors.txt
- Title: Slammed Doors: Diversity and/as Harassment (paper for the panel "Thinking of Leaving", University of York, 6 March 2020)
- Author: Sara Ahmed. Date: 17 March 2020. Where: feministkilljoys.com
- URL: https://feministkilljoys.com/2020/03/17/slammed-doors/
- How obtained: fetch.py. Saved: whole post.

## 2022-complaint-as-a-queer-method.txt
- Title: Complaint as a Queer Method
- Author: Sara Ahmed. Date: 24 March 2022. Where: feministkilljoys.com
- URL: https://feministkilljoys.com/2022/03/24/complaint-as-a-queer-method/
- How obtained: fetch.py. Saved: whole post.

## 2016-resignation.txt
- Title: Resignation
- Author: Sara Ahmed. Date: 30 May 2016. Where: feministkilljoys.com
- URL: https://feministkilljoys.com/2016/05/30/resignation/
- How obtained: fetch.py. Saved: whole post (short).

## 2017-complaint-as-diversity-work.txt
- Title: Complaint as Diversity Work
- Author: Sara Ahmed. Date: 10 November 2017. Where: feministkilljoys.com
- URL: https://feministkilljoys.com/2017/11/10/complaint-as-diversity-work/
- How obtained: curl + stdlib HTML-to-text, entry-content only (review, 2026-10-12). Saved: whole post (~2,000 words). Its opening line is quoted in How they work.

## 2018-on-complaint-wheeler-centre-captions.txt
- Title: Sara Ahmed: On Complaint (The Wheeler Centre, Melbourne)
- Author: Sara Ahmed. Date: uploaded 29 Oct 2018 (YouTube), 1:03:53
- URL: https://www.youtube.com/watch?v=4j_BwPJoPTE
- How obtained: `yt-dlp --skip-download --write-auto-sub --write-sub --sub-lang en --sub-format vtt -o yt-4j_BwPJoPTE <url>` then `python3 -I vtt2txt.py ... out.txt`
- Saved: whole lecture, auto-captions with timestamps. Only clean lines are quoted.

## 2024-travelling-with-the-feminist-killjoy-captions.txt
- Title: Sara Ahmed: Travelling with the Feminist Killjoy
- Author: Sara Ahmed. Date: uploaded 16 Oct 2024 (Women's and Gender Studies Collection, YouTube), 1:11:08
- URL: https://www.youtube.com/watch?v=qM2zRrw2gy8
- How obtained: yt-dlp as above. Saved: whole lecture, auto-captions. Not quoted on the card.

## 2021-duke-book-pages.txt
- Titles: Queer Phenomenology (Duke, Dec 2006); The Promise of Happiness (Duke, Apr 2010); Living a Feminist Life (Duke, Mar 2017); Complaint! (Duke, Sep 2021)
- URLs: https://www.dukeupress.edu/queer-phenomenology ; https://www.dukeupress.edu/the-promise-of-happiness ; https://www.dukeupress.edu/living-a-feminist-life ; https://www.dukeupress.edu/complaint
- How obtained: fetch.py. Saved: first 2,500 characters of each page. The "Read the Introduction" PDFs for Living a Feminist Life and Complaint! were downloaded but their text could not be extracted cleanly without a PDF library; not saved.

## 2023-feminist-killjoy-handbook-publisher-pages.txt
- Titles: The Feminist Killjoy Handbook, Penguin UK page (Penguin paperback, ISBN 9781802061895); The Bookseller, "Allen Lane signs Ahmed's 'stirring' guide..." (16 May 2022)
- URLs: https://www.penguin.co.uk/books/454793/the-feminist-killjoy-handbook-by-ahmed-sara/9781802061895 ; https://thebookseller.com/rights/allen-lane-signs-ahmeds-stirring-guide-to-feminist-thought-and-action-in-five-way-auction
- How obtained: fetch.py. Saved: Penguin page (first 3,500 characters); the Bookseller headline and lead.

## 2026-saranahmed-contact.txt
- Title: Contact, saranahmed.com
- URL: https://www.saranahmed.com/contact
- How obtained: fetch.py. Saved: page text.

## Not saved, link only
- "Losing Your Hand: Complaint, Common Sense, and Other Institutional Legacies", Stanford Humanities Center, 2023: https://www.youtube.com/watch?v=wNBbKrktEy0 (captions fetched, not saved).
- David Higham Associates author page (agent Nicola Chang): https://davidhigham.co.uk/?p=36554 (site returned 403 to the fetch tool; confirmed via WebFetch only).

## Checks
Quotes on the card, with file and location:
1. "Heterosexuality: a path that is kept clear." — `2018-queer-use.txt`, paragraph beginning "Heterosexuality:" (after the well-trodden path passage).
2. "The post box has provided a home for nesting birds. Intended functionality can mean who something is for, not just what something is for." — `2018-queer-use.txt`, paragraph beginning "If the toilet was occupied because it was in use".
3. "A job description becomes a wall description." — `2020-slammed-doors.txt`, paragraph beginning "In my earlier project on diversity".
4. "They happen “behind closed doors,” which is why there are so many doors in these stories." — `2022-complaint-as-a-queer-method.txt`, paragraph beginning "Complaints are made confidential as soon as they are lodged."
5. "the personal is institutional" — `2018-on-complaint-wheeler-centre-captions.txt`, [00:25:33].
Card phrases in How they work / Hooks: "is all about ears" (2022 post, paragraph beginning "By “complaint as queer method,”"); "can be understood as vandalism: “the willful destruction of what is venerable and beautiful.”" (2018 post, Conclusion: Queer Vandalism); "the gap between what is supposed to happen and what does happen is densely populated" (Wheeler captions [00:10:50]–[00:10:56]); "The more a path is used the more a path is used." (2018 post); "something can be used by those for which it was not intended" (2018 post, post box paragraph); "the geography of a place the building the long corridors are locked doors the windows with blinds that can come down" (Wheeler captions [00:05:08]–[00:05:11]); "A door can be shut after you enter. A door can be shut because you enter." (2020 post, paragraph beginning "For those who are deemed dependent on doors being opened").

Unconfirmed: nothing on the card. Note: the Allen Lane 2023 hardback is confirmed by The Bookseller report and the Penguin page (Penguin imprint for the paperback); no Allen Lane-imprint page was fetched. Her former title at Goldsmiths is not stated on the card.
Review 2026-10-12: all five card quotes and the seven hook/method fragments re-grepped and found verbatim; Duke pages (Queer Phenomenology Dec 2006, Living a Feminist Life Mar 2017, Complaint! Sep 2021, both introduction PDFs linked), Penguin page (paperback 7 Mar 2024), saranahmed.com/contact and the David Higham page (agent Nicola Chang) re-fetched; Allen Lane hardback 2023 (ISBN 9780241619537) seen on Waterstones via web search, not fetched; all six YouTube/blog links resolve.
