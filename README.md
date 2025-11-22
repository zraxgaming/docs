# Zdev Docs Starter Kit

Use this starter kit to get your docs deployed and ready to customize for Zdev.

Click the green **Use this template** button at the top of this repo to copy the starter kit. The starter kit contains examples with

- Guide pages
- Navigation
- Customizations
- API reference pages
- Use of popular components

**[Follow the full quickstart guide](https://starter.zdev.com/quickstart)**

## Development

Install the Zdev CLI (example package name: `zdev`) to preview your documentation changes locally. To install, use the following command:

```
npm i -g zdev
```

Run the following command at the root of your documentation, where your `docs.json` is located:

```
zdev dev
```

View your local preview at `http://localhost:3000`.

## Publishing changes

Install the Zdev GitHub app from your dashboard to propagate changes from your repo to your deployment. Changes are deployed to production automatically after pushing to the default branch.

## Need help?

### Troubleshooting

- If your dev environment isn't running: Run `zdev update` (or check the CLI docs) to ensure you have the most recent version of the CLI.
- If a page loads as a 404: Make sure you are running in a folder with a valid `docs.json`.

### Resources
- Zdev documentation: https://zdev.com/docs
