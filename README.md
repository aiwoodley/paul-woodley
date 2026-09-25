# paul-woodley

Personal brand site for Paul Woodley. It is plain static HTML/CSS/JS with no build step, deployed on Netlify.

**Status: DRAFT.** The page carries `noindex`, and dashed amber boxes mark placeholders.

## Links out to
- DigiLabs TechTank: https://www.digi-labs.org
- DigiLabs ITAD: https://digilabs-itad.netlify.app
- Woodley Solutions / Woodley Brothers Networks: https://woodleynetworkingsolutions.netlify.app
- Peter's site: https://peter-woodley.netlify.app

## Paul must provide or approve before launch
- [x] Portrait + 9 personal photos added (resized, metadata stripped). The RCG ship selfie was left out on purpose: employer branding
- [x] Triathlon (Ocean Key) photo, bike/Miami, basketball, marina, fountain added
- [ ] Still needed: DigiLabs lab/giveaway photo
- [ ] Optional captions: macaw, marina/mountain, forest fountain locations
- Left out on purpose: RCG hard-hat selfie + Voyager of the Seas model (employer branding), shirtless jungle shot (tone). Easy to add back
- [ ] The two DigiLabs lab videos (desktop teardown, drive sanitization). They are in the Muse workspace, not on this machine
- [x] Work history, degree, certs, volunteering filled from public LinkedIn
- [ ] Title conflict: LinkedIn says "Application Engineer" (Jul 2024–present), Muse says "Systems Engineer, IT Shipboard Gaming". Site uses the Muse title. Confirm and update LinkedIn to match
- [ ] OK to name Bloom Medicinals (cannabis operator) publicly? It's already on LinkedIn
- [ ] The public one-liner for the RCG role. Check it against RCG's outside-activity / social media policy
- [ ] Confirm "co-founder" wording for DigiLabs (the Muse prompt said "Founder"; Peter's says cofounder)
- [ ] Next travel stop (optional)
- [ ] Approve all copy

## Launch
1. Remove `<meta name="robots" content="noindex, nofollow">` from `index.html` and the `X-Robots-Tag` header from `netlify.toml`
2. Remove the `.draft-bar` div
3. Push to `main`. Netlify auto-deploys

Contact form submissions go to Netlify Forms (Site → Forms). Turn on email notifications there.
