<svelte:options tag="svelte-component-ts" />

<script>
    import Hello from './components/Hello.svelte';
    import { reverse } from './utils/reverse';
    let message = 'Hello world!';
</script>

<div class="un-scoped-class">
    <div class='section has-text-centered'>
        <h1 class='title'>{message}</h1> 
        <button class='button'>Click Me!</button>
        <Hello />
    </div>
    
</div>

<!-- We need both of these for some reason?? -->
<svelte:head>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bulma@0.9.3/css/bulma.min.css">
</svelte:head>

<style>
    @import "https://cdn.jsdelivr.net/npm/bulma@0.9.3/css/bulma.min.css";
    /* Some styles are needed to be able to inject sub styles currently, probably need to hack more to avoid this requirement 🤷‍♂️*/
    .un-scoped-class {
        background-color: inherit;
    }
</style>
