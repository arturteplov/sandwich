# sandwich

Static website for requesting paid customer interviews and registering interest in participating.

## Current behavior

- A researcher can submit the people they want to interview, project details, timing, and recruiting budget.
- A potential participant can describe their experience and leave contact information.
- A separate privacy/contact form accepts questions and data requests.
- Netlify Forms stores submissions. The operator reviews requests and coordinates conversations manually.
- No account creation, automatic participant matching, interview scheduling, or in-app payment processing is implemented.

## Files and deployment

The `site/` directory contains the public website, privacy page, confirmation pages, Netlify headers, and robots.txt.

For a repository-connected Netlify deployment, use `site` as the publish directory. The HTML pages can be opened locally, but Netlify Forms submissions require deployment on Netlify.

Forms are named `research-requests`, `participant-interest`, and `privacy-contact`.

## Test status

One test submission to the researcher form was previously confirmed in Netlify. The participant and privacy forms have not been independently confirmed with live submissions.

No participant submissions, customer data, private operating records, API keys, or credentials are included in this repository.

The repository is public. No open-source license has been assigned.
