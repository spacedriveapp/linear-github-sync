# Linear GitHub Sync

This is a system to synchronize Linear issues to GitHub issues when a specific tag tag is added to the Linear issue. Spacedrive uses this to allow contributors to work with us without having to give them access to our internal Linear team.

## Usage

Ensure you have the [Vercel CLI](https://vercel.com/docs/cli) installed globally on your machine!

```bash
git clone https://github.com/spacedriveapp/linear-github-sync.git
cd linear-github-sync/
cp .env.example .env # Also add your API keys into the .env file!
pnpm i
vercel dev
```

Once you've started the server make sure to set the Webhook URL for both Linear and GitHub, if you don't know how click [here](https://a.com).

Please feel free to join our [Discord](https://discord.gg/XzDj6gXf28) or create an issue on this repository if you need any help
