# english-lessons

Lesson pages and listening files for private English tutoring, served by GitHub Pages.

    https://<username>.github.io/english-lessons/

## Layout

    index.html              landing page
    robots.txt              tells search engines to stay out
    .nojekyll               stops GitHub Pages hiding folders that start with _
    misheel/
      index.html            her page: listening files, then lessons
      lessons/*.html        the SHARE pages, exactly as used in the lesson
      listen/<n>/index.html a player page - this is what the QR code opens
      audio/*.mp3           the cut exam audio

Backstage pages are **not** in here and must never be. They hold the answer keys.

## Adding next week's listening

1. Drop the new `listening-<n>.mp3` into `misheel/audio/`.
2. Copy an existing `misheel/listen/<n>/` folder, change the number, the title,
   the duration and the one-line description.
3. Add a card for it at the top of `misheel/index.html`.
4. Commit and push. Pages redeploys in about a minute.

## Note on the material

The recordings and question text are Cambridge past papers, reproduced here for one
student's private study. The repository has to be public for GitHub Pages to serve it
on a free plan, so `robots.txt` and a `noindex` tag on every page keep it out of search
results. Do not share the address more widely.
