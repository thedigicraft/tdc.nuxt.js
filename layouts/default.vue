<template>
    <div class="container">
        <header>
            <h1>The Digital Craft</h1>
            <router-link to="/">Home</router-link> | <router-link to="/about">About</router-link>
        </header>
        <main>
            <Nuxt />
        </main>
        <footer>Copyright and such</footer>
    </div>
    
</template>

<style>
    html,
    body,
    #__nuxt,
    #__layout {
        height: 100%;
    }
</style>

<style scoped>
    .container {
        min-height: 100%;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
    }
    header {
        padding: 1rem;
        background-color: #f5f5f5;
    }
    main {
        padding: 1rem;
        flex-grow: 1;
    }
    footer {
        padding: 1rem;
        background-color: #f5f5f5;
    }

</style>