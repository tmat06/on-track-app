<script>

</script>

<nav>
    <section class='left-nav'>
        <div>Logo</div>
        <a href='/write'>Write</a>
        <a href='/calendar'>Calendar</a>
        <a href='/goals'>Goals</a>
    </section>
    <section class='right-nav'>
        <button on:click={() => {console.log('clicked')}}>Settings</button>
        {#if true}
        <div>logged in</div>
        {:else}
        <div>not logged in</div>
        {/if}
    </section>
</nav>
<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<style>
    * {
        font-family: 'Inter san'
    }

    nav, a, button {
        all: unset
    }

    nav {
        display: flex;
        justify-content: space-between;
        align-items: center;
        width: 100%;
        height: 60px;
    }

    .left-nav {
        display: flex;
        gap: 6rem;
    }

    .right-nav {
        display: flex;
        gap: 6rem;
    }

</style>
