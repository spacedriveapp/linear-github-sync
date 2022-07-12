# Linear GitHub Sync

This is a system to synchronize Linear issues to GitHub issues when a specific tag tag is added to the Linear issue. Spacedrive uses this to allow contributors to work with us without having to give them access to our internal Linear team.

## Usage

Ensure you have the [Vercel CLI](https://vercel.com/docs/cli) installed globally on your machine!

```
git clone https://github.com/spacedriveapp/linear-github-sync.git
cd linear-github-sync/
cp .env.example .env # Make sure to fill to fill out your .env file
pnpm i
vercel dev
```

Before you've started the server make sure to fill out the information in the `.env` file, if you don't know how click [here](https://github.com/spacedriveapp/linear-github-sync/wiki).

Please feel free to join our [Discord](https://discord.gg/XzDj6gXf28) or create an issue on this repository if you need any help.
