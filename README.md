# HTML-only CSS color theme switcher with no flash of the wrong theme

Building a CSS-powered theme switcher that allows the user to choose their own theme _and_ doesn’t have a flash when the user chooses a non-default theme has previously required either server rendering or some kind of delayed display with client-side JavaScript.


## No JavaScript required
This example has no build step, no framework, and no client-side JS. It’s just HTML and CSS.

No server required, either! It uses [Netlify Edge Functions](https://docs.netlify.com/edge-functions/overview/) to transform the HTML at the edge node, delivering the right theme immediately.

The Edge Function is the only moving piece in the whole implementation.
