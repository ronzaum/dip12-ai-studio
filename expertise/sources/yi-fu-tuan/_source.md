# Sources: Yi-Fu Tuan

Raw material for the unit card `expertise/unit/yi-fu-tuan.md`. All fetched 2026-10-12.

## 2017-folklore-and-place-four-themes-afs-talk.txt
- Title: Yi-Fu Tuan, "Folklore and Place: Four Themes"
- Author: Yi-Fu Tuan (introduced by an AFS officer)
- Date: YouTube upload 2017-06-13 by the American Folklore Society. The talk is a plenary at an AFS annual meeting; the year is not stated in the captions (the introducer calls *Escapism*, 1998, his new book)
- Where published: YouTube, American Folklore Society channel
- URL: https://www.youtube.com/watch?v=OSJfs0fQnJg
- How obtained: `yt-dlp --skip-download --write-auto-sub --write-sub --sub-lang en --sub-format vtt -o OSJfs0fQnJg <url>` then `python3 -I vtt2txt.py OSJfs0fQnJg.en.vtt out.txt`
- What is saved: whole talk, auto-captions with `[HH:MM:SS]` timestamps (58 min, ~7,300 words). Auto-captions: no punctuation, mis-hearings (e.g. "Pettis" for Pepys, "millio" for milieu).

## 2021-conversation-tuan-olwig-landscape-research-group.txt
- Title: Conversation with Yi Fu Tuan and Kenneth Olwig
- Date: YouTube upload 2021-06-08; Landscape Research Group "Landscape and Goodness" symposium
- URL: https://www.youtube.com/watch?v=C24agoJ202U
- How obtained: same yt-dlp command, then vtt2txt.py
- What is saved: whole conversation, auto-captions with timestamps (57 min, ~7,400 words).

## 2013-belonging-to-this-place-uw-madison.txt
- Title: "Belonging to this place: A conversation with Yi-Fu Tuan"
- Author: Mary Ellen Gabriel, L&S News and Notes; republished on Mad Geog News (UW–Madison Geography)
- Date: 2 May 2013
- URL: https://geography.wisc.edu/madgeognewsdev/2013/05/03/belonging-to-this-place-a-conversation-with-yi-fu-tuan
- How obtained: `python3 -I fetch.py <url> out.txt`
- What is saved: the whole article (~820 words), which quotes Tuan directly.

## 2010-dear-colleague-2010-07-06-public-and-private.txt
- Title: Dear Colleague letter, 6 July 2010 (the public and the private, the body and the mind)
- Author: Yi-Fu Tuan
- Where published: yifutuan.org archive (© Yi-Fu Tuan)
- URL: https://www.yifutuan.org/archive/2010/20100706.htm
- How obtained: fetch.py
- What is saved: the whole letter (~560 words).

## 2010-dear-colleague-2010-03-26-patriotism.txt
- Title: Dear Colleague letter, 26 March 2010 (the small events behind patriotism)
- Author: Yi-Fu Tuan
- URL: https://www.yifutuan.org/archive/2010/20100326.htm
- How obtained: fetch.py
- What is saved: the whole letter (~630 words).

## 2011-surviving-death-essay.txt
- Title: "Surviving Death", special essay for readers of the letters
- Author: Yi-Fu Tuan
- Date: 15 June 2011
- URL: https://www.yifutuan.org/archive/2011/2011survivingdeath.htm
- How obtained: fetch.py
- What is saved: the whole essay (~1,450 words).

## 2008-about-the-dear-colleague-archive.txt
- Title: "About the Yi-Fu Tuan 'Dear Colleague' Archive"
- Author: Melanie McCalmont, webmaster, yifutuan.org
- Date: 15 September 2008
- URL: https://www.yifutuan.org/archive.htm
- How obtained: fetch.py
- What is saved: the whole page (~670 words); includes one line Tuan wrote to McCalmont.

## 2022-uw-madison-obituary.txt
- Title: "UW–Madison mourns influential, beloved geography professor Yi-Fu Tuan"
- Author: Mary Ellen Gabriel, UW–Madison News; republished on MadGeogNews
- Date: 15 August 2022
- URL: https://geography.wisc.edu/madgeognews/2022/08/15/uw-madison-mourns-influential-beloved-geography-professor-yi-fu-tuan
- How obtained: fetch.py
- What is saved: the whole article (~1,000 words).

## 2001-space-and-place-umn-press-page.txt, 1990-topophilia-columbia-up-page.txt, 2013-landscapes-of-fear-umn-press-page.txt
- Publisher pages for the three Works (University of Minnesota Press; Columbia University Press; University of Minnesota Press)
- URLs: https://www.upress.umn.edu/9780816638772/space-and-place/ ; https://cup.columbia.edu/book/topophilia/9780231073950 ; https://www.upress.umn.edu/9780816684595/landscapes-of-fear/
- How obtained: fetch.py
- What is saved: the product page text (title, ISBN, date, description).

## Not saved
- A second UW lecture ("Professor Yi-Fu Tuan", UWLSSVideo, 2015, on cultural diversity) was downloaded but not kept: nothing on the card comes from it.
- No letters earlier than 2010 are online yet at yifutuan.org (the archive index links only 2010 and 2011).

## Checks
Every quote on the card, with file and line (timestamp). Checked by grep on 2026-10-12.
- "place is universal landscape by contrast is a special take on place that is far from being universal" — `2017-folklore-and-place-four-themes-afs-talk.txt`, [00:12:29]–[00:12:36] (four caption lines joined).
- "fear a common element in the experiencing of place in earlier times has diminished in our time" — same file, [00:09:30]–[00:09:37].
- "People think that geography is about capitals, land forms, and so on. But it is also about place — its emotional tone, social meaning, and generative potential." — `2013-belonging-to-this-place-uw-madison.txt` (appears twice: pull quote and body).
- "To be a private person, living in the sheltered home, was to be an idiot." — `2010-dear-colleague-2010-07-06-public-and-private.txt`, first paragraph (line break after "sheltered" in the saved text).
- "the world's fundamental indifference I believe should always be at the back of our mind when we talk of relationships" — AFS talk, [00:47:06]–[00:47:13].
- How they work: "my listening post" — 2013 article; "objective correlative" / "who i am is the desert" — `2021-conversation-tuan-olwig-landscape-research-group.txt`, [00:18:03]–[00:18:10]; "over 700 letters" — about page.
- Hooks: "the proximate senses of touch smell and taste" — AFS talk, [00:12:04]; "is primarily a construction of the dominant sense of sight" — [00:13:07]–[00:13:11]; "from a point above ground level" — [00:12:59]; "even as they reduced fear also revealed its extent" — [00:21:59]–[00:22:05]; "has diminished in our time" — [00:09:37]; "fundamental indifference" — [00:47:06]; "folklore is anchored in place or locality" — [00:16:46]–[00:16:50]; "in the city's forum" — 6 July 2010 letter, first paragraph.
- Works: all three confirmed on fetched publisher pages. Nothing on the card is unconfirmed. The year of the AFS talk itself is not stated in the recording; the card gives the upload year (2017).
