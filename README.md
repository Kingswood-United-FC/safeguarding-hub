# Safeguarding Hub

Who to tell about a safeguarding or welfare concern at Kingswood United FC, how to report it, what happens next, and the club's policies and codes of conduct. For coaches, volunteers, parents and players.

**Live site:** https://kingswood-united-fc.github.io/safeguarding-hub/

## This repository is public

Anyone on the internet can read the site, these files, and every past version of them. Removing something later does not remove it from the history.

Never add:

- details of any safeguarding or welfare concern, case or individual
- personal data beyond the contact details the welfare team has agreed to publish
- drafts the committee has not approved

## What's in here

| Path | What it is |
| --- | --- |
| `index.html` | The whole page: wording, contacts, layout |
| `img/` | Crest, accreditation badge, welfare team photos, QR code |
| `pdf/` | Copies of the policies the page hosts |
| `docs/` | A preview image of every page of those PDFs |
| `.nojekyll` | Tells GitHub to publish the files as they are. Leave alone |

## Updating

**A contact changes** (name, number, age group): edit that person's block in `index.html` under "Who to tell". If the person changes, replace their photo in `img/` using the same file name. Check the same change is needed in the Coach Pocket Guide.

**A hosted policy changes:** replace the PDF in `pdf/` using the same file name, and replace its preview images in `docs/` (one image per page, named `<pdf-name>-1.webp`, `-2.webp` and so on). If the page count changes, update the page count and image list for that document in `index.html`.

**A policy on the club website moves:** update its link in `index.html` under "Our policies and codes of conduct".

**After any change:** update the "Page last updated" date at the bottom of `index.html`, and write a one-line note saying what changed and why when you commit.

The live site updates within a minute or two of a change to the `main` branch.

## Keeping it in step

- The policies are the source of truth. If a policy changes, change this page to match.
- The Coach Pocket Guide (`coach-pocket-guide` repository) repeats the welfare contacts and the emergency plan. Change both together.
- The emergency section follows the Emergency Action Plan (KUFC-EAP-01). Update it whenever that plan is reissued.

## Ownership

Maintained by the Vice-Chair with the Lead Welfare Officer, on behalf of the Kingswood United FC committee. Questions: committee@kingswoodunited.co.uk
