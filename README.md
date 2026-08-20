# AmploPay Docs

Documentation site for the AmploPay Gateway API, built with Mintlify.

## Requirements

- Node.js
- Mintlify CLI

Install the CLI if needed:

```bash
npm i -g mint
```

## Local development

Run the local preview from the repository root:

```bash
mint dev
```

The preview runs at `http://localhost:3000`.

## Validation

Run these checks before publishing changes:

```bash
npx mint validate
npx mint broken-links
npx mint a11y
```

## Structure

- `docs.json`: Mintlify configuration and navigation.
- `introduction.mdx`: Main landing page.
- `authentication.mdx`: Authentication guide.
- `endpoints/`: Gateway API endpoint documentation.
- `webhooks/`: Webhook event documentation.
- `faq/`: Common integration questions.
- `images/`: Logo, icon, and visual assets.

## Publishing

Publishing is handled by Mintlify after the repository is connected through the Mintlify GitHub app. Push changes to the configured production branch to deploy.
