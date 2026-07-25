# H1B Levels

H-1B salary data for AI & tech companies.

This data is more accurate than other salary sites that rely on self-reporting. These are legally required filings—companies must certify these wages with the Department of Labor.

**Note:** This is base salary only. Employers are not required to report stock or bonuses, which can significantly increase total compensation.

## Data

- **Source:** [DOL OFLC LCA Disclosure Files](https://www.dol.gov/agencies/eta/foreign-labor/performance)
- **Releases:** FY2025 Q4 and FY2026 Q2
- **Determinations:** Oct 2024 – Mar 2026
- **Records:** 2,333 filings

## Companies

42 AI-native and high-growth tech companies including Cursor, Anthropic, OpenAI, Databricks, and more.

## Deployment (CI/CD)

This repo is a static site. CI/CD is configured to deploy to Vercel.

- **Production:** the `main` branch deploys to production.
- **Previews:** every other branch push gets a preview URL to test PRs before merging.

### Setup

1. Create a Vercel project for this repo.
2. Add these GitHub repo secrets:
   - `VERCEL_TOKEN`
   - `VERCEL_ORG_ID`
   - `VERCEL_PROJECT_ID`
3. Push any branch and use the preview URL shown in:
   - **Vercel** dashboard, or
   - **GitHub Deployments** on the commit/PR.