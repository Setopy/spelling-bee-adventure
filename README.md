# Word Bee Adventure

A browser based spelling practice garden for young spellers. The site is a single HTML page and does not require a server-side account or service.

## Study source

The word bank contains 4,000 main headwords transcribed from the supplied **2019–2020 Words of the Champions** PDF. It preserves the source's One Bee, Two Bee, and Three Bee sections and marks the 450 School Spelling Bee Study List entries.

The PDF also prints alternate spellings. The app includes clear variants as accepted forms on their matching study cards; alternatives whose parent is unclear in the PDF layout appear as separate source-variant cards. The PDF is an older edition. Its introductory Three Bee count does not match the number of entries in the printed Three Bee sections, so the site reports the counts transcribed from the printed pages (One Bee 800; Two Bee 2,100; Three Bee 1,100). The booklet identifies Merriam-Webster Unabridged as the Bee's official dictionary. The word list itself does not provide definitions, example sentences, or audio.

Confirm the current list and rules with the child's school or competition organizer. Scripps says its 2027 Words of the Champions edition is available to enrolled schools. This independent site is not affiliated with Scripps or Merriam-Webster.

- [Scripps study resources](https://spellingbee.com/study-list)
- [Scripps Words of the Champions FAQ](https://spellingbee.com/faq/what-words-champions)
- [2020 printable guide](https://spellingbee.com/sites/default/files/inline-files/Words_of_the_Champions_Printable_FINAL.pdf)

## Features

- Browse and search 4,000 main headwords and the printed alternate spellings by tier and by school-list membership.
- Study cards with family-entered meanings, sentences, and verified spelling or word-part clues.
- Listening and spelling checks, multiple-choice spelling, missing-letter, and scramble practice.
- Ten-word mock bee rounds, review scheduling, progress tracking, and custom word-list entry.
- Local browser storage only: notes, custom words, and progress do not sync between devices.

Speech playback uses the voice installed in the visitor's browser. It is not official Bee pronouncer audio. Use the dictionary link to verify unfamiliar words, pronunciation, meanings, and word origins.

## Publish

GitHub Pages serves `index.html` from the repository root. The page is self-contained; the word bank is embedded in `index.html`.

## Install on a phone and track children separately

Word Bee Adventure is an installable Progressive Web App (PWA). Open `https://spellingbee.luzkids.org/` in a supported phone browser and choose **Install app**. On iPhone or iPad, open it in Safari, tap Share, then **Add to Home Screen**. On Android, open it in Chrome and choose **Install app** from the browser menu.

The opening player picker uses a child’s first name or nickname and a Bible-character avatar (David, Esther, Noah, Daniel, Ruth, Moses, Mary, or Joseph). No email or password is collected. Each profile keeps its own word attempts, correct recalls, review queue, notes, study days, and streak on that browser/device. Existing single-player progress migrates to the first profile created.

Profiles are a household player picker, not authenticated accounts. Data stays in the browser’s local storage and is not uploaded or synchronized across phones. Use the same device and browser to continue the same profile. If families need cross-device sync, add a private family account/backend before promising synced progress.

The app shell and word bank can be cached for offline opening after the first online visit. Some browser speech voices and dictionary links still need connectivity or device support.
