# Sources: Timothy Morton

Raw material for the unit card `expertise/unit/timothy-morton.md`. All fetched 2026-10-12. `cfetch.py` is the scratchpad curl-based page saver (plain `Mozilla/5.0` user agent; timothy-morton.com blocks the default one); `fetch.py` is the urllib one.

## 2011-dawn-of-the-hyperobjects-talk.txt
- "Dawn of the Hyperobjects", Timothy Morton. Keynote given in 2011 (his description: "a keynote I gave in 2011 when I was first developing the Hyperobjects concept"); uploaded to his own YouTube channel 18 Nov 2023. 39 min.
- URL: https://www.youtube.com/watch?v=Lc7hs6UuDZo
- How: `yt-dlp --skip-download --write-auto-sub --write-sub --sub-lang en --sub-format vtt -o yt/dawn-hyperobjects <url>`, then `python3 -I vtt2txt.py yt/dawn-hyperobjects.en.vtt`, HTML entities unescaped. Auto-captions: no punctuation, some mishearings.
- Saved: whole talk with `[HH:MM:SS]` stamps.

## 2011-new-apps-interview.txt
- "New APPS Interview: Timothy Morton", by John Protevi, New APPS group blog, February 2011. Live page is gone (404); Wayback Machine copy.
- URL: https://web.archive.org/web/2012/http://www.newappsblog.com/2011/02/new-apps-interview-timothy-morton.html
- How: `python3 -I cfetch.py <url> newapps-archive.txt`, cut to the interview text (from "Today's New APPS Interview" to the end of his last answer).
- Saved: the interview in full (about 4,000 words).

## 2016-go-to-hell-blog.txt, 2016-im-dead-blog.txt, 2025-deliver-us-from-evil-blog.txt
- Blog posts by Timothy Morton on timothy-morton.com. The site lists "Go To Hell" and "I'm Dead" as July 6, 2016 and "Deliver Us From Evil" as May 25, 2025. Note: "I'm Dead" mentions Threads, so the 2016 date on the site looks wrong; cited as "dated July 6, 2016 on the site".
- URLs: https://timothy-morton.com/go-to-hell/ · https://timothy-morton.com/im-dead/ · https://timothy-morton.com/deliver-us-from-evil-unleashed/
- How: `python3 -I cfetch.py <url> <out>`, site navigation and footer stripped.
- Saved: each post in full.

## 2017-guardian-profile-blasdel.txt
- "A reckoning for our species: the philosopher prophet of the Anthropocene", Alex Blasdel, The Guardian (The long read), 15 June 2017. A profile; Morton's words appear as quoted speech.
- URL: https://www.theguardian.com/world/2017/jun/15/timothy-morton-anthropocene-philosopher
- How: `python3 -I cfetch.py <url> guardian.txt`, then excerpted.
- Saved: about 3,100 words, the passages with his quoted speech; `[...]` marks cuts.

## 2019-interview-magazine.txt
- "Ecological Philosopher Timothy Morton on Saving the World, Sour Patch Kids, and Versace Shirts", Interview Magazine, 14 March 2019.
- URL: https://interviewmagazine.com/culture/ecological-philosopher-timothy-morton-on-saving-the-world-sour-patch-kids-and-versace-shirts
- How: `python3 -I cfetch.py <url> interviewmag.txt`, chrome stripped. Saved in full.

## 2026-timothy-morton-com-about.txt · 2026-rice-faculty-page.txt
- His About/CV page (excerpt, first 700 words) and the Rice University profile (full). URLs: https://timothy-morton.com/about/ · https://profiles.rice.edu/faculty/timothy-morton
- How: cfetch.py; Rice needed `curl -A "curl/8.4.0"` (406 for browser agents), then the same HTML parser.

## 2013-umn-hyperobjects-page.txt · 2016-cup-dark-ecology-page.txt · 2018-penguin-being-ecological-page.txt · 2024-cup-hell-page.txt
- Publisher pages for the four Works (University of Minnesota Press; Columbia University Press x2; Penguin UK). Fetched with `fetch.py`, trimmed to the book data and blurb. The MIT Press page for Being Ecological returned 403, so the Penguin UK page is the record.

## Checks
Each quote on the card, where it is in the saved file:
- "tectonic plates global warming nuclear radiation evolution these are hyperobjects entities that are massively distributed in time and space at least relative to human scales": `2011-dawn-of-the-hyperobjects-talk.txt` lines 12–15, [00:00:23]–[00:00:35].
- "there is no exit from this situation thus the time of hyperobject is a time of sincerity that is a time in which it's impossible to achieve a final distance towards the world": same file, lines 252–256, [00:12:36]–[00:12:48].
- "global warming spells the end of the world not in an apocalypse but in an abject living on in the absence of a meaningful life world bounded by a distant Horizon": same file, lines 784–787, [00:37:34]–[00:37:46].
- "Europe tried to incarnate Paradise on Earth and therefore created Hell: a concentration camp, plantation world.": `2016-go-to-hell-blog.txt` line 21.
- "Go out in the street and start making any and as many kinds of political affiliations with as many kinds of beings, human or otherwise, that you possibly can": `2017-guardian-profile-blasdel.txt` line 42.
- How they work: "If it's a book, 2000 words per day…" and "print, scribble, redo…": `2011-new-apps-interview.txt` line 13; writing in bed / music: line 16. "I'm not on social media": `2016-im-dead-blog.txt` line 8. Libretto and collaborators: `2026-timothy-morton-com-about.txt` line 6.
- Hooks: "massive non-human non-sentient entities": talk file line 20 [00:00:45]. "the Earth is a house for us all" and "we discover ourselves on the inside of some big objects bigger than us": lines 669–671 [00:32:01].
- Works: all four publisher pages fetched and saved (see above). Hell: CUP page says May 2024 (the Rice page says 2025; CUP is the record).

Unconfirmed: nothing on the card. Caveat only: the blog's own dates for "Go To Hell" and "I'm Dead" (July 6, 2016) are doubtful, see above; the card cites them as the site dates them. Lead mentioned Guardian and Frieze interviews: the Guardian piece is the Blasdel profile (saved); no Frieze interview with Timothy Morton was found (frieze results are for the critic Tom Morton).
