# Remix 3 Resources

This repository contains a collection of useful links relating to [Remix 3](https://remix.run/blog/wake-up-remix) — what it is, how it works, how it integrates with other libraries, and what the community is building.

Feel free to submit a PR if there's something interesting you'd like to share!

## Announcements

- [Wake up, Remix! - Michael Jackson and Ryan Florence (May 28, 2025)](https://remix.run/blog/wake-up-remix)

  "It's time to go wake up Remix! Here's what we're building and what it means for React Router."

## Remix Jam 2025

Links with timestamps are provided for each Remix API, feature or demo introduced within the "Introducing Remix" talks.

- [Remix Jam 2025 live stream](https://www.youtube.com/watch?v=xt_iEOn2a6Y)
  - [Introducing Remix - Part 1 (Components) [3:16:04]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=11764s)
    - [Demo disc reveal [3:24:28]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=12268s)
    - [Intro to Remix component model [3:26:35]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=12395s)
    - [`@remix-run/events` package [3:37:39]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=13059s)
    - [`createInteraction` [3:42:34]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=13354s)
    - [`this.update` to trigger re-renders [3:51:37]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=13897s)
    - [Building the drum machine demo [3:56:01]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=14161s)
    - [`createEventType` for type-safe custom events [4:04:24]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=14664s)
    - [`this.context.set`/`this.context.get` [4:07:46]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=14866)
    - [`this` argument being added to an existing component [4:11:00]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=15060s)
    - [`this.signal` for managing component cleanup [4:21:14]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=15674)
    - [`connect` event to access underlying DOM elements [4:21:14]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=15674s)
    - [`this.queueTask` for executing code after the DOM has been updated [4:27:39]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=16059s)
    - [`@remix-run/events/key` keyboard event helpers [4:32:02]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=16322s)
    - [`event.preventDefault` for skipping subsequent event handlers of the same type [4:34:11]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=16451s)
    - [Cleaning up event handlers from `events` [4:36:10]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=16570s)
    - [Preventing race conditions in async event handlers via `signal` argument [4:42:38]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=16958s)
    - [Preventing race conditions in side-effects from render functions via `signal` argument [4:47:04]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=17224s)
    - [Remix component library [4:49:55]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=17395s)
    - [Bubbling custom events [4:56:18]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=17778s)
    - [Rendering a Remix component inside a web component [4:59:52]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=17992s)
  - [Introducing Remix - Part 2 (Server, routing, hydration and `Frame`) [5:29:21]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=19761s)
    - [Intro to Remix server model [5:31:11]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=19871s)
    - [`createRequestListener` for using fetch handlers in Node servers [5:35:32]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=20132s)
    - [`html` helper for creating HTML responses [5:37:09]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=20229s)
    - [`RoutePattern` for matching URLs to routes with type-safe parameters [5:41:34]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=20494s)
    - [`href` method for type-safe generation of URLs from route patterns [5:47:26]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=20846s)
    - [`route` helper for defining a collection of route patterns [5:49:37]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=20977s)
    - [`createRouter` and `router.map` to bind handlers to routes [5:51:43]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=21103s)
    - [`RouteHandlers` type for ensuring that a handler is defined for every route [5:53:17]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=21197s)
    - [`router.fetch` for routing requests to the correct handler and getting a response [5:54:23]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=21263s)
    - [`router.use` for middleware [5:54:43]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=21283s)
    - [`renderToStream` for rendering Remix components on the server [5:55:22]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=21322s)
    - [Defining routes with different HTTP methods for handling `formData`, and wiring it up to a `form` [6:03:25]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=21805s)
    - [Configuring the router's `formData` parser [6:07:05]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=22025s)
    - [`redirect` helper for returning a redirect response, and why `Response.redirect` is not used [6:08:02]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=22082s)
    - [`css` prop for dynamic CSS generation [6:09:57]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=22197s)
    - [`LocalFileStorage` for handling file uploads [6:14:19]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=22459s)
    - [`resources` helper for defining a RESTful set of routes [6:21:26]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=22886s)
    - [Bookstore app demo [6:25:33]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=23133s)
    - [`formAction` helper for defining a `GET`/`POST` pair of routes [6:26:18]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=23178s)
    - [`storage` property on request context for type-safe request-level storage [6:30:22]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=23422s)
    - [`hydrated` function for partial hydration of server-rendered Remix components [6:31:56]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=23516s)
    - [`createFrame` for bootstrapping a Remix application on the client [6:35:05]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=23705s)
    - [`Frame` component [6:36:00]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=23760s)
    - [`this.frame.reload` method for reloading `Frame` elements on the client [6:48:40]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=24520s)
    - [Inspecting the HTML server response and DOM updates when reloading `Frame` elements [6:50:19]](https://www.youtube.com/watch?v=xt_iEOn2a6Y&t=24619s)

## Demo apps

- [Bookstore demo](https://github.com/remix-run/remix/tree/main/demos/bookstore)

  The Bookstore demo presented at Remix Jam 2025.

- [Remix Jam Demo Disc](https://github.com/kentcdodds/remix-jam)

  Contents of the physical CD given to Remix Jam 2025 attendees, shamelessly bootlegged by Kent C. Dodds. Contains the drum machine demo presented at the conference, plus a few other basic game demos.

- [Remix Jam Drum Machine - Mark II](https://github.com/rossipedia/remix-jam-mk2)

  An improved version of the drum machine demo from Remix Jam 2025, expanded to include a full spectrum analyzer and the ability to edit the drum pattern.

## Third-party integration examples

- [Jotai](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/state-libs/jotai.tsx)
- [Motion](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/animations/motion.tsx)
- [Preact Signals](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/state-libs/signals.tsx)
- [Redux Toolkit](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/state-libs/redux.tsx)
- [RxJS](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/state-libs/rxjs.tsx)
- [TanStack Form](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/tanstack-libs/form.tsx)
- TanStack Query
  - [Using `@tanstack/query-core` APIs directly](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/tanstack-libs/query.tsx)
  - [With a custom Remix-specific `queryCache` function](https://gist.github.com/aleclarson/914a784b7a27a2b5b66358b9f9e0622e)
- [TanStack Table](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/tanstack-libs/table.tsx)
- [TanStack Virtual](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/tanstack-libs/virtual.tsx)
- [XState](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/state-libs/xstate.tsx)
- [Zustand](https://github.com/sergiodxa/remix-v3-examples/blob/main/app/state-libs/zustand.tsx)
