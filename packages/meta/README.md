# @hackersent/meta

React component for generating Open Graph/etc meta tags for Hackersent pages.
Designed for Next.js but framework-agnostic.

Not recommended for non-Hackersent sites—you’ll get Hackersent favicons :)

## Usage

```bash
npm i @hackersent/meta
# yarn add @hackersent/meta
```

Example for [hackersent.com](https://hackersent.com):

```js
// import Head from 'next/head'

<Meta
  as={Head} // component to wrap tags in, defaults to React.Fragment
  name="Hackersent" // site name
  title="Learn cybersecurity" // page title
  description="Learn cybersecurity online for free" // page description
  image="https://hackersent.com/static/card.png" // large summary image URL
  color="#0038CC" // theme color
  manifest="/static/site.webmanifest" // link to site manifest
/>
```

All props are optional. If you include multiple times, the tags from the last
instance will be used.

MIT License
