<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/mckrieger/nextjs-dashboard">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Next.js Dashboard</h3>

  <p align="center">
    A template dashboard for your business
    <br />
    <a href="https://github.com/mckrieger/nextjs-dashboard"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/mckrieger/nextjs-dashboard">View Demo</a>
    ·
    <a href="https://github.com/mckrieger/nextjs-dashboard/issues">Report Bug</a>
    ·
    <a href="https://github.com/mckrieger/nextjs-dashboard/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <!-- <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li> -->
    <li><a href="#technical-features">Technical Features</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

I wanted to create a dashboard that was versatile, customizable, and modern, using lightweight, performant technologies.

Here's why:
* Technology should be sustainable and reusable 
* Reinventing the wheel is a waste of time
* Convenience and customizability are key to customer adoption

Since every project/business is different, I hope to make this dashboard as flexible and reusable as I can. So I'll be adding features, technical enhancements, and bug fixes as time goes on. You may also suggest changes by forking this repo and creating a pull request or opening an issue. Thanks to all the people have contributed to expanding this project!

View the demo by clicking the link above.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* [![Next][Next.js]][Next-url]
* [![React][React.js]][React-url]
* [![TypeScript][TypeScript.com]][TypeScript-url]
* [![Tailwind][Tailwind.com]][Tailwind-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
<!-- ## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

1. Get a free API Key at [https://example.com](https://example.com)
2. Clone the repo
   ```sh
   git clone https://github.com/your_username_/Project-Name.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```js
   const API_KEY = 'ENTER YOUR API';
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p> -->



<!-- USAGE EXAMPLES -->
<!-- ## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

<p align="right">(<a href="#readme-top">back to top</a>)</p> -->



<!-- ROADMAP
## Roadmap

- [x] Add Changelog
- [x] Add back to top links
- [ ] Add Additional Templates w/ Examples
- [ ] Add "components" document to easily copy & paste sections of the readme
- [ ] Multi-language Support
    - [ ] Chinese
    - [ ] Spanish

See the [open issues](https://github.com/mckrieger/nextjs-dashboard/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p> -->

<!-- Technical Features -->
## Technical Features

Because one of my primary aims is to work with the latest technologies to optimize the user experience, I've included this section to highlight what I've done and why it matters.

1. [Tailwind](https://tailwindcss.com/) is a CSS framework that speeds up the development process by allowing you to quickly write [utility classes](https://tailwindcss.com/docs/utility-first) directly in your TSX markup.
2. [CSS Modules](https://nextjs.org/docs/basic-features/built-in-css-support) allow you to scope CSS to a component by automatically creating unique class names, so you don't have to worry about style collisions as well.
	- Also has shared CSS using layout files
3. TypeScript provides type safety, code readability, and improved debugging.
4. [`clsx`](https://www.npmjs.com/package/clsx) is a library that lets you toggle class names easily. We recommend taking a look at [documentation](https://github.com/lukeed/clsx) for more details.
5. Optimized fonts
	- [Cumulative Layout Shift](https://web.dev/cls/) is a metric used by Google to evaluate the performance and user experience of a website. With fonts, layout shift happens when the browser initially renders text in a fallback or system font and then swaps it out for a custom font once it has loaded. This swap can cause the text size, spacing, or layout to change, shifting elements around it.
	- Next.js automatically optimizes fonts in the application when you use the `next/font` module. It downloads font files at build time and hosts them with your other static assets. This means when a user visits your application, there are no additional network requests for fonts which would impact performance.
6. Optimized Images
	- The `<Image>` Component is an extension of the HTML `<img>` tag, and comes with automatic image optimization, such as:
		- Preventing layout shift automatically when images are loading.
		- Resizing images to avoid shipping large images to devices with a smaller viewport.
		- Lazy loading images by default (images load as they enter the viewport).
		- Serving images in modern formats, like [WebP](https://developer.mozilla.org/en-US/docs/Web/Media/Formats/Image_types#webp) and [AVIF](https://developer.mozilla.org/en-US/docs/Web/Media/Formats/Image_types#avif_image), when the browser supports it.
7.  File System Routing
	- Next.js uses file-system routing where **folders** are used to create nested routes. Each folder represents a **route segment** that maps to a **URL segment**.
8. Partial Rendering
	- One benefit of using layouts in Next.js is that on navigation, only the page components update while the layout won't re-render. This is called [partial rendering](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating#3-partial-rendering)
9. [client-side navigation](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating#how-routing-and-navigation-works) 
	- Remove unnecessary re-renders
10. Automatic code-splitting and prefetching
	- To improve the navigation experience, Next.js automatically code splits your application by route segments. This is different from a traditional React SPA, where the browser loads all your application code on initial load.
	- Splitting code by routes means that pages become isolated. If a certain page throws an error, the rest of the application will still work.
11. UUIDs vs. Auto-incrementing Keys
  - We use UUIDs instead of incrementing keys (e.g., 1, 2, 3, etc.). This can make URL params etc. longer; however, UUIDs eliminate the risk of ID collision, are globally unique, and reduce the risk of enumeration attacks - making them ideal for large databases.
12. Seeded with sample data
  - To improve the user experience while demoing, and to improve development and debugging.
13. Search (using URL search params)
	- Benefits of using URL search params:
		- **Bookmarkable and Shareable URLs**: Since the search parameters are in the URL, users can bookmark the current state of the application, including their search queries and filters, for future reference or sharing.
		- **Server-Side Rendering and Initial Load**: URL parameters can be directly consumed on the server to render the initial state, making it easier to handle server rendering.
		- **Analytics and Tracking**: Having search queries and filters directly in the URL makes it easier to track user behavior without requiring additional client-side logic.
  - Debounced Search Bar
  - Paginated Search to enhance performance
14. Server Components
    - Server Components support promises, providing a simpler solution for asynchronous tasks like data fetching. You can use `async/await` syntax without reaching out for `useEffect`, `useState` or data fetching libraries.
    - Server Components execute on the server, so you can keep expensive data fetches and logic on the server and only send the result to the client.
    - Since Server Components execute on the server, you can query the database directly without an additional API layer.
15. SQL Optimization for Scalability
  - You could fetch all the invoices and sort through them using JavaScript. This isn't a problem as our data is small, but as the application grows, it can significantly increase the amount of data transferred on each request and the JavaScript required to sort through it.
  - Instead of sorting through the latest invoices in-memory, you can use an SQL query to fetch only the last 5 invoices.
16. Parallel Data Fetching
  - Start executing all data fetches at the same time, which can lead to performance gains.
  - Use a native JavaScript pattern that can be applied to any library or framework.
17. Loading Skeleton UI
	- Suspense allows you to defer rendering parts of your application until some condition is met (e.g. data is loaded). You can wrap your dynamic components in Suspense. Then, pass it a fallback component to show while the dynamic component loads.
18. Route Groups
	- Create [Route Groups](https://nextjs.org/docs/app/building-your-application/routing/route-groups) (invisible folders) to leverage file system rendering without being forced to apply rules to all pages within.
	- Route groups allow you to organize files into logical groups without affecting the URL path structure.
19. Accessibility
  - Semantic HTML, labelling, and focus outlines are used to help those using assistive technologies to navigate the app.
20.  Server-side form validation
	- By validating forms on the server, you can:
		- Ensure your data is in the expected format before sending it to your database.
		- Reduce the risk of malicious users bypassing client-side validation.
		- Have one source of truth for what is considered _valid_ data.
21. User Authentication and authorization (using NextAuth.js)
  - Authentication is about making sure the user is who they say they are. You're proving your identity with something you have like a username and password.
	- Authorization is the next step. Once a user's identity is confirmed, authorization decides what parts of the application they are allowed to use.
22. Metadata
	- Metadata plays a significant role in enhancing a webpage's SEO, making it more accessible and understandable for search engines and social media platforms. Proper metadata helps search engines effectively index webpages, improving their ranking in search results. Additionally, metadata like Open Graph improves the appearance of shared links on social media, making the content more appealing and informative for users.
23.  Partial Pre-rendering
	- Partial Prerendering is an experimental feature introduced in Next.js 14. It is an experimental feature that allows you to render a route with a static loading shell, while keeping some parts dynamic. In other words, you can isolate the dynamic parts of a route.
	- Currently, if you call a [dynamic function](https://nextjs.org/docs/app/building-your-application/routing/route-handlers#dynamic-functions) inside your route (e.g. `noStore()`, `cookies()`, etc), your entire route becomes dynamic.
	- This is how most web apps are built today. You either choose between static and dynamic rendering for your **entire application** or for a **specific route**.
	- However, most routes are _not_ fully static or dynamic. You may have a route that has both static and dynamic content. For example, consider an [ecommerce site](https://partialprerendering.com/). You might be able to prerender the majority of the product page, but you may want to fetch the user's cart and recommended products dynamically on-demand.
	- When a user visits a route:
		- A static route shell is served, ensuring a fast initial load.
		- The shell leaves holes where dynamic content will load in asynchronous.
		- The async holes are streamed in parallel, reducing the overall load time of the page.
	- Partial Prerendering combines ultra-quick static edge delivery with fully dynamic capabilities and we believe it has the potential to [become the default rendering model for web applications](https://vercel.com/blog/partial-prerendering-with-next-js-creating-a-new-default-rendering-model), bringing together the best of static site generation and dynamic delivery.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

McKean Krieger -  - mckean.krieger@gmail.com

Project Link: [https://github.com/mckrieger/nextjs-dashboard](https://github.com/mckrieger/nextjs-dashboard)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* [Choose an Open Source License](https://choosealicense.com)
* [Img Shields](https://shields.io)
* [GitHub Pages](https://pages.github.com)
* [Font Awesome](https://fontawesome.com)
* [React Icons](https://react-icons.github.io/react-icons/search)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/mckrieger/nextjs-dashboard/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/mckrieger/nextjs-dashboard/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/mckrieger/nextjs-dashboard/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/mckrieger/nextjs-dashboard/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/mckrieger/nextjs-dashboard/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 