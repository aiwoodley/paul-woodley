# paul-woodley

Personal brand site for Paul Woodley. It is plain static HTML/CSS/JS with no build step, deployed on Netlify.

**Status: DRAFT.** The page carries `noindex`, and dashed amber boxes mark placeholders.

## Links out to
- DigiLabs TechTank: https://www.digi-labs.org
- DigiLabs ITAD: https://digilabs-itad.netlify.app
- Woodley Solutions / Woodley Brothers Networks: https://woodleynetworkingsolutions.netlify.app
- Peter's site: https://peter-woodley.netlify.app

## Paul must provide or approve before launch
- [ ] Portrait photo (no stock photos of people)
- [ ] Gallery photos: travel, triathlon, running, family, DigiLabs
- [ ] The two DigiLabs lab videos (desktop teardown, drive sanitization). They are in the Muse workspace, not on this machine
- [ ] LinkedIn URL, or: past roles, dates, FSU degree/major and year, certifications
- [ ] The public one-liner for the RCG role. Check it against RCG's outside-activity / social media policy
- [ ] Confirm "co-founder" wording for DigiLabs (the Muse prompt said "Founder"; Peter's says cofounder)
- [ ] Next travel stop (optional)
- [ ] Approve all copy

## Launch
1. Remove `<meta name="robots" content="noindex, nofollow">` from `index.html` and the `X-Robots-Tag` header from `netlify.toml`
2. Remove the `.draft-bar` div
3. Push to `main`. Netlify auto-deploys

Contact form submissions go to Netlify Forms (Site → Forms). Turn on email notifications there.
