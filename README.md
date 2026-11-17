# Sentence variety practice

A self-contained Ventura College ENGL C1000 lesson with 12 comprehension checks, writing practice, and a one-page PDF reference. The focus is on rhetorical moves and sentence variety: emphasizing, connecting, framing, and combining ideas. Sentence-type labels serve as reference vocabulary.

## Publish from GitHub to Netlify

1. Upload the contents of this folder to the root of your GitHub repository. Keep `public/index.html` and the PDF together inside `public`.
2. In Netlify, import the GitHub repository and select the branch to deploy.
3. Leave the build command blank. The included `netlify.toml` sets the publish directory to `public`. No package installation or build is required.
4. Deploy, then open the published site URL. Check one question, the PDF download, and saving after a refresh before sharing the URL with students.

If you place this entire folder inside a larger repository instead, set Netlify's base directory to this folder so its configuration and `public` directory are used.

## Files

- `public/index.html`: lesson, styling, and scripts in one file.
- `public/sentence-variety-handout.pdf`: printable one-page reference.
- `netlify.toml`: publish-folder configuration.

## Student work

Responses are stored in localStorage in the current browser for this site's origin. They do not sync between devices or different site URLs, and clearing browser data can remove them. A visible notice reports when storage is unavailable. Students can download their responses as text or print them, and can clear their saved work on a shared device. Downloads are not submissions.

The lesson code sends no student responses to a server and includes no analytics, external scripts, fonts, or form-processing integration. Netlify hosting has its own request logging. This lesson does not produce instructor completion records or grades. Do not enable Netlify Forms for these practice checks.

## Maintenance

Edit `public/index.html` directly. Answer keys are zero-based `data-key` values on each check form; keep them aligned with radio values if you reorder choices. If you substantially change questions or writing fields, change the `storageKey` version to avoid restoring incompatible older responses.

Grammar references are linked in the lesson footer. No license grant has been added; choose a repository license if you want to specify reuse permissions.
