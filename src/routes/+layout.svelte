<script lang="ts">
    import type { LayoutData } from './$types';
    import '../app.css';
    export let data: LayoutData;
</script>


<nav>
    <ul>
        <li><a href="/">Home</a></li>
        <li><a href="/about">About</a></li>
    </ul>

</nav>

<main>
    <slot />
</main>
