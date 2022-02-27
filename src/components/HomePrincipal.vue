<template>
    <div class="up">
        <div class="card card-up">
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
        <div class="card card-up">
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
        <div class="card card-up">
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
.up {
    display: flex;
    margin-left: 6%;
    margin-right: 6%;
    margin-top: 45px;}

.card-up p {
    text-align: justify;
}
@media (max-width: 1280px){
.up {
    align-items: center;
    flex-direction: column;
    /*flex-basis: 80vw;*/
}


.card-up {
    margin-top: 18px;
}
.card-img-top {
    max-width: 80%;
    align-self: center;
} }

@media  (min-width: 990px){
    .card-up {
    max-width: 70vw;
    
}

}

@media (min-width: 1280px)  {
    .up {
        justify-items: center;
        flex-direction: row;
    }
    .card-up {
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