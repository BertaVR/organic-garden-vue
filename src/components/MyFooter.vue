<template>
    <footer class="text-center text-white">
        <!-- Grid container -->
    
        <section class="mb-4">


      <a class="btn btn-outline-light btn-floating m-1 media fb" role="button">
<i class="fa fa-facebook fa-xl" aria-hidden="true"></i></a>


      <a class="btn btn-outline-light btn-floating m-1 media tw" role="button"
        ><i class="fa fa-twitter fa-xl" aria-hidden="true"></i>
</a>


      <a class="btn btn-outline-light btn-floating m-1 media gh" role="button"
        ><i class="fa fa-github" aria-hidden="true"></i>
</a>
    </section>
        <!-- Copyright -->
        <div class="text-center p-3" style="background-color: rgba(0, 0, 0, 0.2);">
            © 2022 Copyright:
            <router-link class="text-white" exact-active-class="active" to="/">Organic Garden</router-link>
        </div>
        <!-- Copyright -->
    </footer>
</template>

<style>
footer {
    margin-top: 20px;
    background-color: #255a23;
}
i{
font-size: 80pt;
}
a.tw{
   background-color: #00acee;
}
a.tw:hover{  background-color: #33c5ff;
}
a.tw:focus{
       background-color: #00acee;

}
a.fb{  background-color: #043294;
}
a.fb:hover{  background-color: #083fb6;
}
a.fb:focus{  background-color: #043294;
}

a.gh{
    background-color: #333;
}
a.gh:hover{
    background-color: rgb(73, 73, 73);
}
a.gh:focus{
    background-color: #333;
}
i{font-size: 20pt;}
</style>