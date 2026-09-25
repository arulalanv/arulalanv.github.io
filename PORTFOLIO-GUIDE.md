# Updating the academic portfolio

The redesigned homepage retains the existing Jekyll build. Blog posts, About, projects, feeds and legacy styles remain in place. The original post listing is now at /blog/. The new stylesheet is portfolio.css, avoiding a collision with Jekyll's generated style.css. Do not add .nojekyll.

## Update content
Open editor.html (locally or on the website), add approved alumni profiles, or edit publications/news in the JSON field. Download content.js and replace that file on an update branch in this repository. Review and merge the change to publish it. The editor never uploads data or authenticates to GitHub; downloading does not update the website.

## Alumni details needed
Provide batch years, student names, project/achievement, role, organisation or university, and optional LinkedIn link. Include only details approved for public display. Never put private records in content.js; filtering does not hide source data from the public repository. No student records have been invented.

## Regular review
Review publications, news and alumni achievements monthly or quarterly. Confirm a preferred cadence before scheduling automatic reviews. Automatic publishing is not configured.

## Validation and content review
Internal anchors, local asset paths and JavaScript syntax checked. Full browser/Jekyll validation remains pending because the environment has no browser or Ruby runtime. The draft should be reviewed before merge.

The M.Tech. year follows the existing About page (2015). Recent selected publications and activities were supplied in the owner's prior context and need final bibliographic review. The broken resume.pdf link is replaced with Request CV; add a current CV PDF when available. Biography remains in index.html; publications, news and alumni are in content.js.
