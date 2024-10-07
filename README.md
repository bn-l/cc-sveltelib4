

# Svete 4 component library template

Designed to be used as a starter for making a svelte 4 component library.

From the [svelte docs on packaging](https://kit.svelte.dev/docs/packaging):

"When you're creating an app, the contents of src/routes is the public-facing stuff; src/lib contains your app's internal library."

"A component library has the exact same structure as a SvelteKit app, except that src/lib is the public-facing bit, and your root package.json is used to publish the package. src/routes might be a documentation or demo site that accompanies the library, or it might just be a sandbox you use during development."

I.e.: The lib part is the part that gets built and is intended to be imported as a componet from another svelte project and the src part with routes is there for demos of the components etc.

## Todo:

- [ ] Add github actions script to publish demo to netlify.