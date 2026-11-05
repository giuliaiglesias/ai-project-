# AI, in real life

A responsive, single-page student explainer about artificial intelligence. Built with plain HTML and CSS. No packages, API keys, tracking or build step.

## Files

- `index.html`: complete website, factual source links and AI acknowledgement.
- `styles.css`: responsive layout, colours, focus states and print styles.
- `assets/`: available for future images; the current graphics use HTML and CSS.

## Preview

Open `index.html` in a browser. Or run `python3 -m http.server 8000` inside this directory and open http://localhost:8000.

## Publish with GitHub Pages

1. Sign in to GitHub and create a **public** repository named **ai-project**. Leave the initial README option unchecked because this project already includes one.
2. Choose **uploading an existing file** on the empty repository page.
3. Extract the ZIP, then upload `index.html`, `styles.css` and `README.md` directly into the repository root. Do not upload the outer `ai-project` folder or the ZIP itself. The empty assets folder is optional.
4. Commit the files to `main`.
5. Open **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**, then **main** and **/ (root)**. Save.
6. Wait for deployment, then open the published URL and check it on desktop and mobile. Publication can take several minutes.

For the username shown in the supplied screenshot, the expected URLs are:

- Website: https://giuliaiglesias.github.io/ai-project/
- Repository: https://github.com/giuliaiglesias/ai-project

These are expected destinations, not confirmation that a repository or deployment exists. Submit them only after both open successfully.

## Explain the work

- HTML uses `header`, `nav`, `main`, `section`, `article`, `figure` and `footer` to organise meaning.
- CSS Grid creates columns and media queries stack them for phones.
- The diagram summarises training and inference; it is not a complete model architecture.
- The electricity bars compare 415 TWh and 945 TWh, from the IEA's 2025 report. The first bar is 415/945 × 100 = 43.915% of the second. The 2030 value is a projection, not a measured result. The figures cover all data centres.
- The thought experiment uses native `details` and `summary`, which work without JavaScript.
- Links point from claims to a source list and then to original publications.
- No external fonts or imagery are needed. The decorative hero graphic is hidden from screen readers; the informative graphics have text equivalents and captions.

## Checks completed

Static validation passed for the under-1,000-word limit, process-note length, internal anchor links, unique IDs and stylesheet reference. Browser rendering could not be tested in the build environment because no browser executable was available and the browser download failed. Verify mobile and desktop rendering and keyboard navigation before submission.

## Before submission

Read the wording and adapt any personal statements to your own views. Read the three sources, understand the HTML and CSS, and verify the published site. The process note accurately states that ChatGPT drafted the writing and code; it does not claim that you already performed the review. After personally reviewing and testing, you may update the acknowledgement to describe your actual contribution.

## AI assistance

ChatGPT (https://chatgpt.com/) generated the initial writing, structure and code and assisted with source verification and local checks. The student author must review the final material and remains responsible for the submission.
