<template>
    <div class="down">
        <!--<div class="line">-->
        <div class="card-and-title">
            <h5 class="card-title">Magazine & Books</h5>
            <div class="card card-down">
                <br />
                <p class="card-text">
                    This is just a placeholder.
                    <br />This is just a placeholder.
                </p>
                <img class="card-img-top reduce-less" src="../assets/resources/magazine.webp" alt="Card image of books" />
                <div class="card-body"></div>
            </div>
        </div>
        <div class="card-and-title">
            <h5 class="card-title">Gallery</h5>
            <div class="card card-down">
                <div>
                    <br />
                    <h6 class="card-subtitle mb-2 text-muted">This is just a place holder.</h6>
                </div>
                <img class="card-img-top reduce" src="../assets/resources/girls.webp" alt="Card image of a young couple of girls" />
                <div class="card-body">
                    <a class="btn btn-dark">View all photos</a>
                </div>
            </div>
        </div>

        <!-- </div>-->
        <!--<div class="line">-->
        <div class="card-and-title">
            <h5 class="card-title">Suppliers Directory</h5>
            <div class="card card-down">
                <div class="card-body">
                    <h6 class="card-subtitle mb-2 text-muted">This is just a place holder.</h6>
                    <span class="card-text">This is just a place holder.</span>
                    <a  class="card-link">(+36) 924-068-207</a>
                </div>
                <div class="card-body">
                    <h6 class="card-subtitle mb-2 text-muted">This is just a place holder.</h6>
                    <span class="card-text">This is just a place holder.</span>
                    <a class="card-link">(+36) 924-068-207</a>
                </div>
            </div>
        </div>
        <div class="card-and-title">
            <h5 class="card-title">Contact</h5>

            <div class="card card-down">
                <div class="card-body">
                    <div>
                        <b>
                            <span class="card-text">Email:</span>
                        </b>
                        <br />
                        <a class="card-link">company@email.com</a>
                        <br />
                    </div>
                    <div>
                        <b>
                            <span class="card-text">Address:</span>
                        </b>
                        <br />
                        <span
                            class="card-text"
                        >This is just a place holder. This is just a place holder.</span>
                        <br />
                    </div>
                    <div>
                        <b>
                            <span class="card-text">Phone:</span>
                        </b>
                        <br />
                        <a  class="card-link">117-683-9187-000</a>
                        <br />
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- </div>-->
</template>
<style>
h6 {
    font-weight: bold;
}

@media (max-width: 340px) {
    .down {
        margin-top: 30px;
        display: grid;
        grid-template-rows: 3fr 3fr 2fr 2fr;
        grid-template-columns: 1fr;
        justify-items: center;
    }
    .card-and-title{width: 100vw};
}
@media (min-width: 340px) and (max-width: 990px) {
    .down {
        margin-top: 30px;
        display: grid;
        grid-template-rows: 3fr 2fr;
        grid-template-columns: 1fr 1fr;
        justify-items: center;
    }
    .card-and-title {
        width: 50vw;
    }
}
.card-and-title {
    margin-top: 18px;
    display: flex;
    flex-direction: column;
    max-height: 4
    0%;
}
.card-body {
    display: flex;
    justify-content: space-around;
    flex-direction: column;
}
.card-down h6 {
    text-align: center;
}
.card-down {
    text-align: justify;
    padding-top: 5px;
    flex-grow: 1;
}
@media (min-width: 995px) {
    .down {
        margin-top: 55px;
        display: grid;
        grid-auto-rows: max-content;
        grid-template-rows: 500px;
        grid-template-columns: 1fr 1fr 1fr 1fr;
        flex-direction: row;
        /*flex-basis: 80vw;*/
    }
    .card-down {
        text-align: center;
        align-self: stretch;
        flex-grow: 1;
    }
    .reduce-less {
        max-width: 62%;
        align-self: center;
    }
        .reduce {
        max-width: 59%;
        align-self: center;
    }
}
</style>