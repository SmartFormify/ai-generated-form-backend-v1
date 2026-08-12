# AI-Generated Form Backend Integration Guides

This repository contains platform-specific guides for connecting contact forms from AI-generated websites to [Smartformify](https://www.smartformify.com/). Each guide explains how to create a Smartformify endpoint, add that endpoint to a form, and review submitted responses in the Smartformify dashboard.

> This is a documentation repository. It does not include a frontend application, backend source code, package manifest, or a runnable local service.

## Choose Your Website Builder

Select the guide that matches the tool used to create your website:

| Website builder | Integration guide |
| --- | --- |
| Bolt.new | [bolt-new-web-backend-integration/README.md](bolt-new-web-backend-integration/README.md) |
| Claude | [claude-web-backend-integration/README.md](claude-web-backend-integration/README.md) |
| Codex | [codex-web-backend-integration/README.md](codex-web-backend-integration/README.md) |
| Cursor | [cursor-web-backend-integration/README.md](cursor-web-backend-integration/README.md) |
| Emergent | [emergent-web-backend-integration/README.md](emergent-web-backend-integration/README.md) |
| Vercel v0 | [vercel-web-backend-integration/README.md](vercel-web-backend-integration/README.md) |

## Repository Structure

```text
.
|-- bolt-new-web-backend-integration/
|   |-- README.md                 # Bolt.new integration guide
|   `-- assets/                   # Screenshots used by the guide
|-- claude-web-backend-integration/
|   |-- README.md                 # Claude integration guide
|   `-- assets/                   # Screenshots used by the guide
|-- codex-web-backend-integration/
|   |-- README.md                 # Codex integration guide
|   `-- assets/                   # Screenshots used by the guide
|-- cursor-web-backend-integration/
|   |-- README.md                 # Cursor integration guide
|   `-- assets/                   # Screenshots used by the guide
|-- emergent-web-backend-integration/
|   |-- README.md                 # Emergent integration guide
|   `-- assets/                   # Screenshots used by the guide
|-- vercel-web-backend-integration/
|   |-- README.md                 # Vercel v0 integration guide
|   `-- assets/                   # Screenshots used by the guide
|-- LICENSE
`-- README.md
```

All guide assets are stored in the corresponding `assets/` directory and are linked relatively from that guide's README.

## Setup

There are no dependencies to install and no local server to run. To use a guide:

1. Open the relevant guide from the table above.
2. Create a Smartformify account at [smartformify.com/signup](https://www.smartformify.com/signup).
3. In the Smartformify dashboard, create an endpoint and copy its endpoint URL.
4. In your website project, replace the contact form's submission target (typically its HTML `action` attribute or submit handler) with that endpoint URL.
5. Deploy or save the website, then send a test submission.

## Usage Example

For a standard HTML form, set the form action to the Smartformify endpoint URL you created:

```html
<form action="YOUR_SMARTFORMIFY_ENDPOINT_URL" method="POST">
  <!-- form fields -->
  <button type="submit">Send</button>
</form>
```

If your form submits through JavaScript, update the URL used by its existing submit request instead. See the guide for your website builder for its platform-specific walkthrough and screenshots.

## Configuration and Response Handling

The only configuration described by these guides is a Smartformify endpoint URL. Use a separate endpoint when you want to keep submissions from different forms separate.

After a form is connected, submissions are available in the Smartformify dashboard's responses area. The included guides also describe email notifications for new submissions. This repository does not define or expose its own API routes, environment variables, authentication scheme, or data model.

## Contributing

Contributions that improve the clarity and accuracy of the guides are welcome.

1. Keep documentation and screenshots specific to the relevant website builder.
2. Use repository-root-relative links in the root README and guide-relative links within each guide.
3. Confirm every added local link points to a file that exists in the repository.
4. Preserve the existing guide structure: each platform directory contains its `README.md` and an `assets/` directory.
5. Submit changes with a concise description of the platform and documentation update.

## License

This project is available under the [MIT License](LICENSE).
