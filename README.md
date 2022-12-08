# Pretty Graham

Like most entreprenurs in the world, I read Paul Graham's website weekly. He has some of the most thoughtful, and interesting takes on everything from [startups](http://www.paulgraham.com/ds.html) to [having kids](http://www.paulgraham.com/kids.html).

However as a designer, I can't help but cringe every time I read Paul Graham's website. Don't get me wrong, the guy has some seriously insightful thoughts on everything from startups to raising kids. But let's be real, his website looks like it was made in the 90s. So I've decided to take matters into my own hands and give his blog a much-needed facelift.

Now, before you start sending angry emails, let me be clear: all of the content on the new and improved site is still straight from Paul's brilliant mind. I just made it a little easier on the ol' eyes. Check the OG out for yourself at [paulgraham.com](<(http://www.paulgraham.com/index.html)>).

And Paul, if you're reading this, please don't sue me. I'm just trying to help 🙏

## Features

- Easy styling customization with [Tailwind 3.0](https://tailwindcss.com/blog/tailwindcss-v3) and primary color attribute
- Near perfect lighthouse score - [Lighthouse report](https://www.webpagetest.org/result/221104_AiDc59_4WF/)
- Lightweight, 45kB first load JS, uses Preact in production build
- Mobile-friendly view
- Light and dark theme
- Self-hosted font with [Fontsource](https://fontsource.org/)
- Supports [plausible](https://plausible.io/), [simple analytics](https://simpleanalytics.com/) and google analytics
- [MDX - write JSX in markdown documents!](https://mdxjs.com/)
- Server-side syntax highlighting with line numbers and line highlighting via [rehype-prism-plus](https://github.com/timlrx/rehype-prism-plus)
- Math display supported via [KaTeX](https://katex.org/)
- Citation and bibliography support via [rehype-citation](https://github.com/timlrx/rehype-citation)
- Automatic image optimization via [next/image](https://nextjs.org/docs/basic-features/image-optimization)
- Flexible data retrieval with [mdx-bundler](https://github.com/kentcdodds/mdx-bundler)
- Support for tags - each unique tag will be its own page
- Support for multiple authors
- Blog templates
- TOC component
- Support for nested routing of blog posts
- Newsletter component with support for mailchimp, buttondown, convertkit, klaviyo, revue, and emailoctopus
- Supports [giscus](https://github.com/laymonage/giscus), [utterances](https://github.com/utterance/utterances) or disqus
- Projects page
- Preconfigured security headers
- SEO friendly with RSS feed, sitemaps and more!

## Todo

1. Improve navigation
2. Add blog posts
3. Deploy on Vercel

## Installation

```bash
npm install
```

## Development

First, run the development server:

```bash
npm start
```

or

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.
