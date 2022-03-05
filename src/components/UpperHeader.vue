<template>
    <!-- Navbar -->
    <a class="link-header" href="#">
        <div class="p-5 text-center bg-image page-header">
            <router-link class="centered" to="/">
                <img class="mb-3 title" alt="Header, image of leaves" src="../assets/title.png" />
            </router-link>
            <h1 class="mb-3 bold">Join our organic farm</h1>
        </div>
    </a>
</template>

<style>
@media (min-width: 992px) {
    .page-header {
        height: 250px;
    }
}
a.link-header {
    text-decoration: none;
}
div.page-header {
    height: 400px;
    position: relative;
    color: #062717;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-content: center;
    background-image: linear-gradient(
            rgba(255, 255, 255, 0.8),
            rgba(248, 253, 245, 0.98)
        ),
        url(../assets/header.jpg);
    background-size: cover;
    top: 0px;
    right: 0px;
    bottom: 0px;
    left: 0px;
}
@media (max-width: 470px) {
    img.title {
        width: 70vw;
    }
}
.bold {
    font-weight: 700;
}

.centered {
    align-self: center;
}
</style>
<script>
// @ is an alias to /src
