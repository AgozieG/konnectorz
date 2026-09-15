# KonnectorZ Real Estate

Mobile-first frontend-only real estate website built with React, TypeScript, Vite, Tailwind CSS and Lucide icons.

## Pages

- Home: cinematic hero, advanced 3D/parallax presentation and featured properties
- Listings: compact search with a hidden advanced filter drawer
- Property Detail: multi-image gallery, specifications and enquiry actions
- Services
- Locations
- About
- Contact

## Advanced property filters

- Keyword search
- Purpose: For Sale / For Rent / Short Let
- Location
- Property type
- Bedrooms
- Bathrooms
- Toilets
- Min/max price
- Furnished / Unfurnished
- Features and amenities

## Run locally

```bash
npm install
npm run dev
```

Build for production:

```bash
npm run build
```

## Notes

The property records and photos in this frontend are demonstration content. Replace the `properties` array in `src/App.tsx` with KonnectorZ's real catalogue before production use.

The site is frontend-only. WhatsApp and phone buttons are direct client-side links.

The supplied KonnectorZ logo is included at `public/resources/logo.png`.
