# Remix 3 Resources

This repository contains a collection of useful links relating to [Remix 3](https://remix.run/blog/wake-up-remix) — what it is, how it works, how it integrates with other libraries, and what the community is building.

Feel free to submit a PR if there's something interesting you'd like to share!

## Announcements

- [Wake up, Remix! - Michael Jackson and Ryan Florence (May 28, 2025)](https://remix.run/blog/wake-up-remix)

  "It's time to go wake up Remix! Here's what we're building and what it means for React Router."

## Remix Jam 2025

Links with timestamps are provided for each Remix API, feature or demo introduced within the "Introducing Remix" talks.

- [Introducing Remix - Part 1 (Components)](https://www.youtube.com/watch?v=iZl0IKj0HHc)
  - [Demo disc reveal [08:21]](https://youtu.be/iZl0IKj0HHc?t=501)
  - [Intro to Remix component model [10:28]](https://youtu.be/iZl0IKj0HHc?t=628)
  - [`@remix-run/events` package [21:32]](https://youtu.be/iZl0IKj0HHc?t=1292)
  - [`createInteraction` [26:27]](https://youtu.be/iZl0IKj0HHc?t=1587)
  - [`this.update` to trigger re-renders [35:30]](https://youtu.be/iZl0IKj0HHc?t=2130)
  - [Building the drum machine demo [39:54]](https://youtu.be/iZl0IKj0HHc?t=2394)
  - [`createEventType` for type-safe custom events [48:17]](https://youtu.be/iZl0IKj0HHc?t=2897)
  - [`this.context.set`/`this.context.get` [51:39]](https://youtu.be/iZl0IKj0HHc?t=3099)
  - [`this` argument being added to an existing component [54:53]](https://youtu.be/iZl0IKj0HHc?t=3293)
  - [`this.signal` for managing component cleanup [1:05:07]](https://youtu.be/iZl0IKj0HHc?t=3907)
  - [`connect` event to access underlying DOM elements [1:05:07]](https://youtu.be/iZl0IKj0HHc?t=3907)
  - [`this.queueTask` for executing code after the DOM has been updated [1:11:32]](https://youtu.be/iZl0IKj0HHc?t=4292)
  - [`@remix-run/events/key` keyboard event helpers [1:15:55]](https://youtu.be/iZl0IKj0HHc?t=4555)
  - [`event.preventDefault` for skipping subsequent event handlers of the same type [1:18:04]](https://youtu.be/iZl0IKj0HHc?t=4684)
  - [Cleaning up event handlers from `events` [1:20:03]](https://youtu.be/iZl0IKj0HHc?t=4803)
  - [Preventing race conditions in async event handlers via `signal` argument [1:26:31]](https://youtu.be/iZl0IKj0HHc?t=5191)
  - [Preventing race conditions in side-effects from render functions via `signal` argument [1:30:57]](https://youtu.be/iZl0IKj0HHc?t=5457)
  - [Remix component library [1:33:48]](https://youtu.be/iZl0IKj0HHc?t=5628)
  - [Bubbling custom events [1:40:11]](https://youtu.be/iZl0IKj0HHc?t=6011)
  - [Rendering a Remix component inside a web component [1:43:45]](https://youtu.be/iZl0IKj0HHc?t=6225)
- [Introducing Remix - Part 2 (Server, routing, hydration and `Frame`)](https://www.youtube.com/watch?v=dZbZgxWlzr8)
  - [Intro to Remix server model [00:30]](https://youtu.be/dZbZgxWlzr8?t=30)
  - [`createRequestListener` for using fetch handlers in Node servers [04:51]](https://youtu.be/dZbZgxWlzr8?t=291)
  - [`html` helper for creating HTML responses [06:28]](https://youtu.be/dZbZgxWlzr8?t=388)
  - [`RoutePattern` for matching URLs to routes with type-safe parameters [10:53]](https://youtu.be/dZbZgxWlzr8?t=653)
  - [`href` method for type-safe generation of URLs from route patterns [16:45]](https://youtu.be/dZbZgxWlzr8?t=1005)
  - [`route` helper for defining a collection of route patterns [18:56]](https://youtu.be/dZbZgxWlzr8?t=1136)
  - [`createRouter` and `router.map` to bind handlers to routes [21:02]](https://youtu.be/dZbZgxWlzr8?t=1262)
  - [`RouteHandlers` type for ensuring that a handler is defined for every route [22:36]](https://youtu.be/dZbZgxWlzr8?t=1356)
  - [`router.fetch` for routing requests to the correct handler and getting a response [23:42]](https://youtu.be/dZbZgxWlzr8?t=1422)
  - [`router.use` for middleware [24:02]](https://youtu.be/dZbZgxWlzr8?t=1442)
  - [`renderToStream` for rendering Remix components on the server [24:41]](https://youtu.be/dZbZgxWlzr8?t=1481)
  - [Defining routes with different HTTP methods for handling `formData`, and wiring it up to a `form` [32:44]](https://youtu.be/dZbZgxWlzr8?t=1964)
  - [Configuring the router's `formData` parser [36:24]](https://youtu.be/dZbZgxWlzr8?t=2184)
  - [`redirect` helper for returning a redirect response, and why `Response.redirect` is not used [37:21]](https://youtu.be/dZbZgxWlzr8?t=2241)
  - [`css` prop for dynamic CSS generation [39:16]](https://youtu.be/dZbZgxWlzr8?t=2356)
  - [`LocalFileStorage` for handling file uploads [43:38]](https://youtu.be/dZbZgxWlzr8?t=2618)
  - [`resources` helper for defining a RESTful set of routes [50:45]](https://youtu.be/dZbZgxWlzr8?t=3045)
  - [Bookstore app demo [54:52]](https://youtu.be/dZbZgxWlzr8?t=3292)
  - [`formAction` helper for defining a `GET`/`POST` pair of routes [55:37]](https://youtu.be/dZbZgxWlzr8?t=3337)
  - [`storage` property on request context for type-safe request-level storage [59:41]](https://youtu.be/dZbZgxWlzr8?t=3581)
  - [`hydrated` function for partial hydration of server-rendered Remix components [1:01:15]](https://youtu.be/dZbZgxWlzr8?t=3675)
  - [`createFrame` for bootstrapping a Remix application on the client [1:04:24]](https://youtu.be/dZbZgxWlzr8?t=3864)
  - [`Frame` component [1:05:19]](https://youtu.be/dZbZgxWlzr8?t=3919)
  - [`this.frame.reload` method for reloading `Frame` elements on the client [1:17:59]](https://youtu.be/dZbZgxWlzr8?t=4679)
  - [Inspecting the HTML server response and DOM updates when reloading `Frame` elements [1:19:38]](https://youtu.be/dZbZgxWlzr8?t=4778)

## Demo apps

- [Bookstore demo](https://github.com/remix-run/remix/tree/main/demos/bookstore)

  The Bookstore demo presented at Remix Jam 2025.

- [Remix Jam Demo Disc](https://github.com/kentcdodds/remix-jam)

  Contents of the physical CD given to Remix Jam 2025 attendees, shamelessly bootlegged by Kent C. Dodds. Contains the drum machine demo presented at the conference, plus a few other basic game demos.

- [Remix Jam Drum Machine - Mark II](https://github.com/rossipedia/remix-jam-mk2)

  An improved version of the drum machine demo from Remix Jam 2025, expanded to include a full spectrum analyzer and the ability to edit the drum pattern.


## Third-Party Integration Examples

### State Management

- [idb](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/storage/idb.tsx)
- [Jotai](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/state-libs/jotai.tsx)
- [Legend State](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/state-libs/legend-state.tsx)
- [localForage](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/storage/localforage.tsx)
- [Nano Stores](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/state-libs/nanostores.tsx)
- [Preact Signals](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/state-libs/signals.tsx)
- [Redux Toolkit](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/state-libs/redux.tsx)
- [RxJS](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/state-libs/rxjs.tsx)
- TanStack Query
  - [Using `@tanstack/query-core` directly](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/tanstack-libs/query.tsx)
  - [Using a custom Remix adapter](https://gist.github.com/aleclarson/914a784b7a27a2b5b66358b9f9e0622e)
- [Valtio](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/state-libs/valtio.tsx)
- [XState](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/state-libs/xstate.tsx)
- [XState Store](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/state-libs/xstate-store.tsx)
- [Zustand](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/state-libs/zustand.tsx)

### Headless UI

- [TanStack Form](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/tanstack-libs/form.tsx)
- [TanStack Table](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/tanstack-libs/table.tsx)
- [TanStack Virtual](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/tanstack-libs/virtual.tsx)

### Animation

- [Motion](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/animations/motion.tsx)

### i18n

- [FormatJS](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/i18n/formatjs.tsx)
- [i18next](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/i18next.tsx)

### Other

- [Tiptap](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/rich-text/tiptap.tsx) - Rich text editor
- [Fuse.js](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/search/fuse.tsx) - Fuzzy search
- [match-sorter](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/search/match-sorter.tsx) - Best-match array sorting

## Web API Integration Examples

- [`BroadcastChannel` for inter-tab communication](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/web-api/broadcast-channel.tsx)
- [Drag and Drop API](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/web-api/drag-drop.tsx)
- [`document.visibilityState` and `visibilitychange` event for detecting when the page is `visible` or `hidden`](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/web-api/page-visibility.tsx)
- [`EventTarget` for custom state management](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/state-libs/event-target.tsx)
- [`fullscreenchange` event handler for full screen mode detection](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/web-api/fullscreen.tsx)
- [`IntersectionObserver` for detecting when elements are in the viewport](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/web-api/intersection-observer.tsx)
- [`let` for mutable component state](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/state-libs/vanilla.tsx)
- [`localStorage`](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/storage/local-storage.tsx)
- [`navigator.share` for triggering the device's native share interface](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/web-api/share.tsx)
- [`Notification`](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/web-api/notification.tsx)
- [`navigator.clipboard`](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/web-api/clipboard.tsx)
- [`navigator.geolocation`](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/web-api/geolocation.tsx)
- [`ResizeObserver`](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/web-api/resize-observer.tsx)
- [`screen.orientation` and `orientationchange` event](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/web-api/screen-orientation.tsxhttps://github.com/sergiodxa/remix-v3-examples/blob/main/app/web-api/screen-orientation.tsx)
- [Web Animations API](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/web-api/web-animations.tsx)

## Experiments

- [vite-plugin-remix](https://github.com/jacob-ebey/vite-plugin-remix)

  Adds support for the `"use client"` directive to automatically pass components through Remix's `hydrated()` function, with added support for chunking.
