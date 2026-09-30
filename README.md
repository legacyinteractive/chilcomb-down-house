# Chilcomb Down House

New Cloudflare Worker website for Chilcomb Down House, Winchester.

## Deployment

The production Worker is named `chilcomb-down-house`. Connect this repository to the existing Worker in Cloudflare under **Settings → Build**.

Use:

- Production branch: `main`
- Build command: leave blank
- Deploy command: `npx wrangler deploy`
- Root directory: repository root

Every push to `main` will then trigger a Cloudflare Workers Build and deployment.

## Preview health check

`/api/health`

The enquiry form remains in preview mode until its destination mailbox and anti-spam controls are approved.
