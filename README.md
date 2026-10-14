# PlateScan privacy website

Publication target: `https://victorcarciu.github.io/platescan-privacy/`

This separate static website contains no scripts, trackers, cookies, build system, application source, or secrets. English is the default page and Romanian is available at `/ro/`.

## Final review before publication

- Obtain operator/legal confirmation that the GDPR legal bases, international-transfer wording, user-rights wording, and 18+ audience are appropriate for the launch.
- Confirm production-account retention and data-sharing configurations for OpenAI, Render, Firebase/Google Analytics, Expo/EAS, and Apple. The policy deliberately states no unverified retention periods.
- Complete a final Romanian legal/translation review.
- Confirm `VictorCarciu/platescan-privacy` does not contain unrelated content before creating or pushing it.

## Local review

Open `index.html` and `ro/index.html`, or serve this directory with a local static HTTP server. Verify at 320, 375, and 430 CSS pixels, keyboard navigation, visible focus, 200% zoom, and both language links.

## Publication procedure after approval

1. Confirm `VictorCarciu/platescan-privacy` does not already exist or is an empty repository intended for this site.
2. Initialize this directory as a Git repository and commit only `index.html`, `ro/index.html`, `styles.css`, and this README.
3. Create the public repository without overwriting an existing repository, then push the default branch.
4. Enable GitHub Pages from the default branch and repository root.
5. Verify `https://victorcarciu.github.io/platescan-privacy/`, `/ro/`, HTTPS, language and email links, mobile layout, keyboard focus, and 200% zoom.
6. Only after the URL is live, configure `EXPO_PUBLIC_PRIVACY_POLICY_URL=https://victorcarciu.github.io/platescan-privacy/` in the established production EAS environment.
7. Release that app configuration only through a separately approved PlateScan release process.
