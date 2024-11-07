# Biome Svelte 5 linter error reproduction

Please go to `src/e-linkpower-client-operator`, it's a SvelteKit project using latest Svelte 5 with my `biome.json` inside.

Then check inside `lib/components/screens/account/AccountLogin.svelte`, you should see Biome linter show error at the line define the state using `let` keyword.

