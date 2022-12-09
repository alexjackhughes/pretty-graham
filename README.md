# Pretty Graham

You can see this live here at [prettygraham.com](https://prettygraham.com/blog).

Like most entreprenurs in the world, I read Paul Graham's website weekly. He has some of the most thoughtful, and interesting takes on everything from [startups](http://www.paulgraham.com/ds.html) to [having kids](http://www.paulgraham.com/kids.html).

However as a man of pixels, I can't help but cringe every time I read Paul Graham's website. Don't get me wrong, he's amazing. But let's be real, his website looks like it was made in the 90s. So I've decided to take matters into my own hands and give his blog a much-needed facelift.

Now, before you start sending angry emails, let me be super clear: all of the content on the new and improved site is still straight from Paul's brilliant mind. I just made it a little easier on the ol' eyes. Check the OG out for yourself at [paulgraham.com](http://www.paulgraham.com/index.html).

And Paul, if you're reading this, please don't sue me 🙏

## Notes

Due to how I scraped the data, I couldn't keep the paragraghs formatting so instead I wrote a function that roughly splits text by character count. I'm guessing most people won't notice, but there's not shot I'm pressing enter a billion times.

## Features

- I've included the python script in "/scraping" for people curious about how I got the articles
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

## Deploy

**Vercel**  
The easiest way to deploy the template is to use the [Vercel Platform](https://vercel.com) from the creators of Next.js. Check out the [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

**Netlify**
[Netlify](https://www.netlify.com/)’s Next.js runtime configures enables key Next.js functionality on your website without the need for additional configurations. Netlify generates serverless functions that will handle Next.js functionalities such as server-side rendered (SSR) pages, incremental static regeneration (ISR), `next/images`, etc.

See [Next.js on Netlify](https://docs.netlify.com/integrations/frameworks/next-js/overview/#next-js-runtime) for suggested configuration values and more details.

**GitHub Pages / Firebase etc.**  
As the template uses `next/image` for image optimization, additional configurations have to be made to deploy on other popular static hosting websites like [Firebase](https://firebase.google.com/) or [GitHub Pages](https://pages.github.com/). An alternative image optimization provider such as Imgix, Cloudinary or Akamai has to be used. Alternatively, replace the `next/image` component with a standard `<img>` tag. See [`next/image` documentation](https://nextjs.org/docs/basic-features/image-optimization) for more details.

The API routes used in the newsletter component cannot be used in a static site export. You will need to use a form API endpoint provider and substitute the route in the newsletter component accordingly. Other hosting platforms such as Netlify also offer alternative solutions - please refer to their docs for more information.

**Google App Engine**
Apart from changes mentioned above for `next/image`, configurations should be changed based on recommendations [here](https://github.com/vercel/next.js/discussions/12474#discussioncomment-17844) in order to set up the project for GAE deployment.

## Support

Using the template? Support this effort by giving a star on GitHub, sharing your own blog and giving a shoutout on Twitter or becoming a project [sponsor](https://github.com/sponsors/timlrx).

## Licence

[MIT](https://github.com/timlrx/tailwind-nextjs-starter-blog/blob/master/LICENSE) © [Timothy Lin](https://www.timlrx.com)
