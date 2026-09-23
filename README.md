# Senior Spelling Bee Pronouncer

AG Spelling Bee Contest – Senior Category word list (2,133 words) with part of speech, definition and recorded British English pronunciation.

## Use it offline
Keep this folder together and double-click `index.html`. Every recording is stored in the `audio` folder, so no internet is needed (the optional "Microsoft Sonia (online)" voice needs internet and Microsoft Edge).

## Put it on GitHub Pages (free, public)

The whole folder is about 41 MB. GitHub's limit is 25 MB **for one file**, and the largest file here is 8 MB, so every file is allowed. But uploading all of them in one go can fail, so upload them in small groups.

1. Sign in at github.com and create a new **public** repository, for example `senior-spelling-bee`.
2. **Upload 1.** Choose **Add file → Upload files**, drag in `index.html`, `README.md` and `.nojekyll`, then **Commit changes**.
3. **Upload 2.** Choose **Add file → Upload files** again. Drag in the **audio** folder itself, but with only `part-1.js` and `part-2.js` inside it. Commit.
   - Easier way: in the upload box, drag the two files in, then before committing, click the file name area and type `audio/` in front of each name so the path reads `audio/part-1.js`.
4. **Uploads 3 and 4.** Repeat with `part-3.js` and `part-4.js`, then `part-5.js` and `part-6.js`. Each one must end up inside the `audio` folder.
5. Check the repository: you should see `index.html`, `README.md`, `.nojekyll` and one folder called `audio` holding all 6 files.
6. **Settings → Pages**: *Deploy from a branch*, branch **main**, folder **/ (root)**, **Save**.
7. After a minute or two the page is live at `https://YOUR-USERNAME.github.io/senior-spelling-bee/`.

If the 6 files end up at the top level instead of inside `audio`, the recorded voice will not play.

## Sources
Definitions: Oxford Learner's Dictionaries and Merriam-Webster.
Recordings: open-source neural text-to-speech (Kokoro, British English voice "Emma"; some words use Kokoro "Lily" or Piper "Jenny/Cori" where clearer), each checked by two automatic speech recognisers. Words that did not pass the check were removed from the list.
