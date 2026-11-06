# Personal Homepage Design

## Goal

Turn the current `academic-homepage` template into a public personal homepage for Wei Cai, using the supplied resume while publishing only the email address. The repository should deploy correctly at the root of `caiwei1030.github.io`.

## Content Structure

- Keep the original template's visual system and Jekyll architecture.
- Set `baseurl` to an empty string for the user-site root path.
- Replace the template identity, biography, education, experience, and awards with resume data.
- Use the portrait from the supplied resume.
- Add a concise projects card for the Anasage optimization system and Tianyan Qmind agent platform.
- Publish the GPR Transformer paper as the only publication.
- Hide news, blog, showcase, and secondary homepage navigation until real content is available.

## Privacy

The homepage exposes `caiwei_1030@163.com` and GitHub only. It does not publish the phone number, WeChat ID, home address, or other personal contact details from the resume.

## Validation

Build the site locally with Jekyll, inspect the generated HTML for stale template names and sensitive contact data, and verify that root-relative assets resolve correctly before pushing to GitHub.
