# H1B Levels

H-1B salary data for AI & tech companies.

This data is more accurate than other salary sites that rely on self-reporting. These are legally required filings—companies must certify these wages with the Department of Labor.

**Note:** This is base salary only. Employers are not required to report stock or bonuses, which can significantly increase total compensation.

## Data

- **Source:** [DOL OFLC LCA Disclosure Files](https://www.dol.gov/agencies/eta/foreign-labor/performance)
- **Range:** Oct 2024 – Sep 2025 (FY2025 Q4)
- **Records:** 751 filings

## Companies

40 AI-native and high-growth tech companies including Cursor, Anthropic, OpenAI, Databricks, and more.

## Deployment (CI/CD)

This repo is a static site. CI/CD is configured to deploy to Cloudflare Pages.

- **Production:** the branch set as the Cloudflare Pages "Production branch" (typically `main`).
- **Previews:** every other branch push gets a preview URL to test PRs before merging.

### Setup

1. Create a Cloudflare Pages project for this repo.
2. Set the production branch in Cloudflare (for example, `main`).
3. Add these GitHub repo secrets:
   - `CLOUDFLARE_API_TOKEN`
   - `CLOUDFLARE_ACCOUNT_ID`
   - `CLOUDFLARE_PAGES_PROJECT` (your Pages project name)
4. Push any branch and use the preview URL shown in:
   - **Cloudflare Pages** dashboard, or
   - **GitHub Deployments** on the commit/PR.