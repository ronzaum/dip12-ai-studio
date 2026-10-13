# Sources: Sun Ra

Raw material for the unit card `expertise/unit/sun-ra.md`. All fetched 2026-10-12. No song lyrics and no poems are saved or quoted; the material is lectures, a talk and an interview.

## 1966-sinclair-interview-intergalactic-discipline.txt
- **Title:** The Intergalactic Discipline of Sun Ra
- **Author:** Sun Ra, interviewed by John Sinclair
- **Date:** taped December 1966; first printed Warren-Forest Sun no. 1 (1967); reprinted Ann Arbor Sun, 5 September 1973
- **Where published:** Ann Arbor District Library, "Old News" OCR archive
- **URL:** https://aadl.org/node/195929
- **How obtained:** `python3 -I fetch.py "https://aadl.org/node/195929" sinclair1966.txt`, then cut to the interview text (header note through the last answer)
- **What is saved:** the whole interview as reprinted (about 1,500 words), freely published online

## 1971-berkeley-lecture-pt1.txt, -pt2.txt, -pt3.txt, -pt4.txt
- **Title:** SUN RA SPEAKS - BERKELEY LECTURE PT 1–4
- **Author:** Sun Ra; uploaded by SUN RA MUSIC CHANNEL (OFFICIAL)
- **Date:** 1971 (UC Berkeley, Afro-American Studies 198, "The Black Man in the Cosmos"); upload date not shown
- **Where published:** YouTube
- **URLs:** https://www.youtube.com/watch?v=Cfy2BpbkGe8 · https://www.youtube.com/watch?v=1LWEQmAGeRQ · https://www.youtube.com/watch?v=lw51E3_BF9s · https://www.youtube.com/watch?v=HotNAXOPxwQ
- **How obtained:** `yt-dlp --skip-download --write-auto-sub --write-sub --sub-lang en --sub-format vtt -o v_<id> <url>` then `python3 -I vtt2txt.py v_<id>.en.vtt v_<id>.txt`
- **What is saved:** the complete YouTube auto-captions with `[HH:MM:SS]` timestamps (pt 1: 28:51, pt 2: 23:58, pt 3: 28:49, pt 4: 12:07). Auto-captions mis-hear words; only lines that read cleanly are quoted.

## 1979-possibility-of-altered-destiny-talk.txt
- **Title:** Sun Ra talks on "The Possibility of Altered Destiny" 11/10/79
- **Author:** Sun Ra; uploaded by KomischeStars
- **Date:** 10 November 1979
- **Where published:** YouTube
- **URL:** https://www.youtube.com/watch?v=rKsMR5YmvyY
- **How obtained:** same yt-dlp and vtt2txt.py commands as above
- **What is saved:** the complete captions with timestamps (1:12:44). Caption origin (uploader or auto) not certain; quote only clean lines.

## Pages fetched for the Works and Contact lines (not saved as text)
- Open Library record for *The Immeasurable Equation* (ISBN 9783833426599): https://openlibrary.org/books/OL32191909M. Record gives the 2006 BoD printing; the lead and a Cleveland Public Library catalogue result (page returned 403, not fetched) give Waitawhile, 2005.
- Criterion Channel page for *Space Is the Place* (1974, dir. John Coney): https://www.criterionchannel.com/space-is-the-place
- Duke University Press page for Szwed, *Space Is the Place* (May 2020 edition): https://www.dukeupress.edu/space-is-the-place
- https://www.sunraarkestra.com/ (front page only, no contact link found) and https://sunramusic.bandcamp.com/ ("Contact Sun Ra" link)
- *The Ark and the Ankh* (Sun Ra and Henry Dumas, 1966): found via search at https://www.soundohm.com/product/the-ark-and-the-ankh; not fetched; no transcript found online.

## Checks
Every quote on the card, where it sits:
- "What I’m talking about is DISCIPLINE – that’s what people need." → `1966-sinclair-interview-intergalactic-discipline.txt`, line 19
- "music is a language and I’m speaking these things over in it. My music is about a better place for people, not to have to die to get there" → same file, line 25
- "I would say that the synonym for myth is happiness" → same file, line 25
- "it's not an innocent thing to belong to a church" → `1971-berkeley-lecture-pt1.txt`, lines 469–470, [00:19:38]–[00:19:40] (the caption line break falls after "innocent")
- "You must appeal to God's impossible department. Because the possible can never save you." → `1979-possibility-of-altered-destiny-talk.txt`, lines 717–719, [00:25:59]–[00:26:06]

Supporting references in How they work and Hooks: pt 1 [00:00:16] words/roots; pt 1 [00:12:57] "just like I would any" other book (line 312); pt 1 [00:10:09] "that's what music is all about" (line 245); pt 1 [00:19:59] "sign your name put your money in" (line 479); pt 2 [00:03:33] "first trumpet sound" (line 92); pt 2 [00:13:22]–[00:14:02] planet as instrument, music of the spheres; 1979 [00:15:43] "You should have schools of discipline." (line 434); Sinclair lines 15 ("the rulers on this planet are in trouble") and 25 ("one age moves over into another one").

Not confirmed / caveats:
- Year of *The Immeasurable Equation*: 2005 (Waitawhile) per the lead and library catalogue snippet; the fetched Open Library record says 2006 (BoD printing). Title and editors confirmed.
- The Berkeley and 1979 texts are YouTube captions, not an authorised transcript. Timestamps are from the caption files.
- The statement that Sun Ra LLC is the estate's holding company comes from web search results (2015 press), not from a page saved here.
- Review 2026-10-12: all five quotes and the hook/method fragments re-grepped and found verbatim; the Lord's Prayer reference corrected to pt 1 [00:03:51]–[00:04:05] ("set formula" at 00:03:51, "Lord's Prayer" at 00:04:05); the unsourced "two-term" claim about the Berkeley course removed. Criterion, Duke (Szwed, May 2020; 1997 original), Soundohm (IKEF, 2001), aadl.org, Bandcamp ("Contact Sun Ra" link present) and sunraarkestra.com re-fetched; all five YouTube links resolve. openlibrary.org refused connections at review time; the 2005 Waitawhile date is also given by an All About Jazz listing (ISBN 3833426594, 2005) seen in web search, not fetched.
