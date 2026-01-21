# Splitwise Clone

A simple expense splitting web application.

## Deployment to Cloudflare Pages

1. Push this repository to GitHub, GitLab, or Bitbucket
2. Log in to [Cloudflare Dashboard](https://dash.cloudflare.com/)
3. Go to Pages > Create a project
4. Connect your Git provider and select the repository
5. Configure the build settings:
   - Framework preset: None
   - Build command: `npm run build`
   - Build output directory: `/` (root directory)
6. Click "Save and Deploy"

## Development

To run locally, simply open `index.html` in a web browser or use a local server like `live-server` or `http-server`.
