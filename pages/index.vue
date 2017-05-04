<template>
    <div class="Container">
        <div class="Inner">
            <h1 class="Title">Hi there!</h1>
            <p>Say hello <a href="http://twitter.com/nevenduranec">@nevenduranec</a>.</p>
        </div>
    </div>
</template>

<style lang="scss">
    .Container {
        min-height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
        text-align: center;
    }

    .Title {
        font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
        font-weight: 700;
        font-size: 100px;
        color: #35495e;
        letter-spacing: 1px;
    }

    p {
        font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
</style>
