<script>
export default {
};
</script>
<template>
    <header>
        <div class="container">
            <nav class="mt-3">
                <div class="d-flex justify-content-between align-items-center">
                    <div>
                        <img src="/dc-logo.png" alt="">
                    </div>
                    <div>
                        <ul class="d-flex">
                            <li>CHARACTERS</li>
                            <li class="active">COMICS</li>
                            <li>MOVIES</li>
                            <li>TV</li>
                            <li>GAMES</li>
                            <li>COLLECTIBLES</li>
                            <li>VIDEOS</li>
                            <li>FANS</li>
                            <li>NEWS</li>
                            <li>SHOP</li>
                        </ul>
                    </div>
                </div>
            </nav>
        </div>
    </header>
</template>


<style scoped>
li {
    padding: 0 .35rem;
    list-style: none;
}
.active{
    color: blue;
    border-bottom: 2px solid blue;
}
</style>