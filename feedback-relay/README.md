# Feedback relay (Cloudflare Worker)

Optional. Lets users send bug reports and feature requests without a GitHub account.
The app posts the report here; the worker files it as a GitHub Issue.

## Setup (optional)

1. Cloudflare account (free tier is enough)
2. GitHub fine-grained PAT with Issues + Contents access to this repo
3. Deploy from this folder with wrangler
4. Set the resulting URL in `config/settings.yaml` under `feedback.relay_url`

If `relay_url` is empty, reports are saved to a local file instead.

See the original project docs for the full worker implementation details if you want to deploy it.
