# how this repo was created:

1. npm create svelte@latest my-app
   1. skeleton project
2. npm cd my-app
3. npm i
4. edit routes
5. run dev

# Routes

## `/`

Unmodified home page

## `/load`

New page with a barebones `+page.server.js` file, returning a promise resolving in 2 seconds with nothing

# Layout

Consists of: 
1. `<li>` nav
2. `{$page.route.id}`
3. `<slot />`

