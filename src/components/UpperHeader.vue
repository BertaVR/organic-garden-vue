<template>
    <!-- Navbar -->
    <div class="p-5 text-center bg-image page-header hojas">
        <h1>
            <img class="mb-3" src="../assets/title.png">
            <h1 class="mb-3">Join our organic farm</h1>
            <small class="mb-3">and learn how to be more eco-friendly</small>

        </h1>
    </div>
</template>

<style>
@media (min-width: 992px) {
    .page-header {
        height: 250px;
    }
}
div.hojas {
    height: 400px;
    position: relative;
    color: #4d3863;
    background-color: #fec8d8;
}
div.hojas::before {
    content: "";
    background-image: url(../assets/header.png);
    background-size: cover;
    position: absolute;
    top: 0px;
    right: 0px;
    bottom: 0px;
    left: 0px;
    opacity: 0.3;
}
</style>
<script>
// @ is an alias to /src
