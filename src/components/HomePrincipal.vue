<template>
    <div class="container">
        <div class="card">
            <div class="card-body">
                <h5 class="card-title">Card title</h5>
                <img class="card-img-top" src="../assets/vegetable.png" alt="Card image cap" />
                <p class="card-text">
                    This is just a place holder, so you can see what the site would look like.
                    This is just a place holder, so you can see what the site would look like. This is just a place holder,
                    so you can see what the site would look like. This is just a place holder, so you can see what the site would look like.
                    This is just a place holder, so you can see what the site would look like. This is just a place holder.
                </p>
                <a href="#" class="btn btn-dark">Read More</a>
            </div>
        </div>
        <div class="card">
            <div class="card-body">
                <h5 class="card-title">Card title</h5>

                <img class="card-img-top" src="../assets/vegetable.png" alt="Card image cap" />
                <p class="card-text">
                    This is just a place holder, so you can see what the site would look like.
                    This is just a place holder, so you can see what the site would look like. This is just a place holder,
                    so you can see what the site would look like. This is just a place holder, so you can see what the site would look like.
                    This is just a place holder, so you can see what the site would look like. This is just a place holder.
                </p>
                <a href="#" class="btn btn-dark">Read More</a>
            </div>
        </div>
        <div class="card">
            <div class="card-body">
                <h5 class="card-title">Card title</h5>

                <img class="card-img-top" src="../assets/vegetable.png" alt="Card image cap" />
                <p class="card-text">
                    This is just a place holder, so you can see what the site would look like.
                    This is just a place holder, so you can see what the site would look like. This is just a place holder,
                    so you can see what the site would look like. This is just a place holder, so you can see what the site would look like.
                    This is just a place holder, so you can see what the site would look like. This is just a place holder.
                </p>
                <a href="#" class="btn btn-dark">Read More</a>
            </div>
        </div>
    </div>
</template>

<style>
.container {
    display: flex;}
@media (max-width: 1280px){
.container {
    align-items: center;
    flex-direction: column;
    /*flex-basis: 80vw;*/
}
.card p {
    text-align: justify;
}

.card {
    margin-top: 18px;
}
.card-img-top {
    max-width: 80%;
    align-self: center;
} }
/*@media  (min-width: 990px){
    .card {
    max-width: 70vw;
}

}*/

@media (min-width: 1280px)  {
    .container {
        justify-items: center;
        flex-direction: row;
    }
    .card {
        margin: 5px;
    }
}
.btn {
    color: white;
    background-color: #255a23;
}

.btn:focus {
    background-color: #255a23;
}
.btn:hover {
    color: white;
    background-color: #3e993b;
}
</style>