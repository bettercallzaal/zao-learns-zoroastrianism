# ZAO learns about Zoroastrianism

Zaal answers the community's questions about Zoroastrianism around the 13th World Zoroastrian Congress (Singapore, 28 to 30 Dec 2026). Questions come by email to zaal@thezao.com. Answers land here as he writes them. Nothing in this repo is private.

## What the site is

A plain static site: HTML and one stylesheet, no framework, no JavaScript, no forms, no analytics, no third-party scripts.

- `index.html` - the intro and the "Ask a question" button. The button opens an email to zaal@thezao.com; there is no hosted form.
- `answers.html` - the list of answers, newest first.
- `style.css` - shared styles (dark navy, gold accent, mobile first).

Open either page straight from the file system to preview it. Nothing needs installing.

## How an answer is added

Each answer is one block in `answers.html`. Copy the commented template at the top of the list, paste it as the first item, and fill in the question, the date and the answer:

```html
<li class="answer">
  <h2>The question, as it was asked</h2>
  <time datetime="2026-11-03">3 Nov 2026</time>
  <p>The answer, in your words.</p>
</li>
```

Use more `<p>` lines for a longer answer. Once the first answer is in, delete the "No answers yet" line.

Leave out the asker's name and email unless they have said it can be public. Everything committed here is public.
