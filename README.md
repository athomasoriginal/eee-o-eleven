##  Eee-O-Eleven

> Someday I'll have me a penthouse.
>
> Stacks and stacks of folding green.
>
> Eee-o-Eleven

Here is an [Eleventy] starter kit.

- [Housekeeping]
- [Quickstart]
- [Feature Choices]
- [Data Usage]
- [Before Dev]
- [Before Deploy]


## Housekeeping

Be sure to have the following tools installed

- [Node]
- [Yarn]

## Quickstart

- Create a project directory
  ```command
  mkdir your-project-name
  ```
  > `your-project-name` is whatever you choose to name your project
- Move into your project directory
  ```command
  cd your-project-name
  ```
- Clone this repo into your project directory
  ```command
  git clone https://github.com/athomasoriginal/eee-o-eleven.git .
  ```
  > The `.` at the end of the above command clones the projects root dirs/files
- Move into the project directory
  ```command
  cd your-project-name
  ```
  > You may want to even rename this directory while your at it
- Install project dependencies
  ```command
  yarn install
  ```
  > Wait for everything to install before running the next step
- Start the project
  ```command
  yarn run dev
  ```

## Feature Choices

This section includes tooling and pattern choices made for this template.

- [HTML5 Boilerplate]
- [Modern CSS Reset]
- A few useful filters:
  - `dateFilter` & `w3DateFilter`
- Example Blog Post
- RSS feed
- Trailing slashes
- Social sharing previews
  - Open Graph
  - Twitter

## Project Commands

- Run development environment
  ```command
  yarn run dev
  ```
- Run development environment in debug mode
  ```command
  yarn run dev:debug
  ```
- Build for production
  ```command
  yarn run build
  ```

## Data Usage

There is a priority order for how Data is consumed by Eleventy.  Familarize yourself with that.  The `_data/site.json` is meant to contain reusable, site related global variables.  Example of what this is not for:  post front matter data.

## Before Dev

- [ ] Update `_data/site.json`

## Before Deploy

- [ ] Add custom favicon
- [ ] Publish sitemap
- [ ] Add analytics tracking
- [ ] Update social media cards - OG, Twitter etc
- [ ] Add Apple Touch Icon
- [ ] Populate web.manifest



[Housekeeping]: #housekeeping
[Quickstart]: #quickstart
[Feature Choices]: #feature-choices
[Data Usage]: #data-usage
[Before Dev]: #before-dev
[Before Deploy]: #before-deploy



[Eleventy]: https://www.11ty.dev/
[Node]: https://nodejs.org/en/
[Yarn]: https://classic.yarnpkg.com/en/docs/install/
[HTML5 Boilerplate]: https://html5boilerplate.com/
[Modern CSS Reset]: https://github.com/andy-piccalilli/modern-css-reset
