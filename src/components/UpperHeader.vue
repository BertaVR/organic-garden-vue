<template>
    <!-- Navbar -->
    <a class="link-header" href="#">
        <div class="p-5 text-center bg-image page-header">
            <h1>
                <img class="mb-3 title" src="../assets/title.png" />
                <h1 class="mb-3 bold">Join our organic farm</h1>
            </h1>
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
    justify-content: center;
    background-image: linear-gradient(
            rgba(255, 255, 255, 0.8),
            rgba(255, 255, 255, 0.98)
        ),
        url(../assets/header.jpg);
    background-size: cover;
    top: 0px;
    right: 0px;
    bottom: 0px;
    left: 0px;
}

.bold {
    font-weight: 700;
}

</style>
<script>
// @ is an alias to /src
