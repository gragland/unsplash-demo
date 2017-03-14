# Unsplash Demo

This is a simple demo app that displays images from [Unsplash](https://unsplash.com) and uses the following React components built by me.

Component                       |    Description
---------------------------|----------------
[Instatype](https://github.com/gragland/instatype)             | Mobile-friendly React autocomplete component. Used for searching Unsplash users.
[React Simple Grid](https://github.com/gragland/react-simple-grid)                    | Display content within a grid of evenly spaced blocks. Features include: ability to hide outer spacing, responsive breakpoints, HOC allowing child components to recieve block width as a prop.
[React Perfect Image](https://github.com/gragland/react-perfect-image)               | Ensures that images take up a desired aspect ratio before the image has finished loading (no page reflow). Also allows us to dynamically change the image source url at different container widths. In conjuction with the React Simple Grid HOC we can ensure we're never loading images at a higher resolution than needed.
[React Scroll Loader](https://github.com/gragland/react-scroll-loader)             | Efficient infinite scroll component used to load more images once we've reached the bottom of the page.
[React Component Data]()           | Async data fetching logic is specified in the component, resolved automagically on server-render, and then passed to the component as props. No more duplication of data fetching logic between client and server.
