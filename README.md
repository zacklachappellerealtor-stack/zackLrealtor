# Zack LaChappelle Real Estate

Five-page Astro website for Zack LaChappelle, REALTOR® with Red 1 Realty, serving Marysville, Union County, and Central Ohio.

## Local development

```sh
npm install
npm run dev
```

## Verification

```sh
npm run check
npm run build
```

## Lead form delivery

The homepage and contact forms share a Formspree-compatible endpoint. Copy `.env.example` to `.env` and set:

```sh
PUBLIC_LEAD_FORM_ENDPOINT=https://formspree.io/f/your-form-id
```

Without this value, the forms stay in demonstration mode and do not transmit visitor information.
