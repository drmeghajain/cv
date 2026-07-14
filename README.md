# Dr Megha Jain Personal Website

A minimal editorial personal website for Dr Megha Jain, built with Next.js, TypeScript, Tailwind CSS and the App Router.

## Setup

```bash
pnpm install
pnpm run dev
```

Open `http://localhost:3000` while developing.

## Checks

```bash
pnpm run build
```

If your installed Next.js version supports it, you can also run:

```bash
pnpm run lint
```

## Content Editing

Most copy, navigation labels, profile links, portfolio cards and research sections live in:

```text
src/content/siteContent.ts
```

Edit that file first for simple content updates.

## Asset Placement

Place the portrait photo here:

```text
public/images/megha-portrait.jpg
```

Place photography images here:

```text
public/images/photography/astitva-01.jpg
public/images/photography/astitva-02.jpg
public/images/photography/portrait-01.jpg
public/images/photography/travel-01.jpg
```

Place the resume PDF here:

```text
public/Megha-Jain-Resume.pdf
```

Place the creative/social sample PDF here:

```text
public/samples/creative-social-samples.pdf
```

The site includes graceful visual placeholders, so missing images will not break the pages during drafting.

## Deployment

The simplest deployment path is Vercel:

1. Push this project to a GitHub repository.
2. Import the repository in Vercel.
3. Use the default Next.js settings.
4. Add the real image and PDF assets before launch.
5. Run a production build during deployment with `pnpm run build`.

Other hosts that support Next.js can also be used. Build with `pnpm run build`, then run with `pnpm run start` where supported.
