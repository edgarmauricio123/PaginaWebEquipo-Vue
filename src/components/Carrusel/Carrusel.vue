<template>
    <div id="carrusel" class="container-fluid" style="background-color: #c6a49a;">
        <div id="carouselExample" class="carousel slide">

            <div class="carousel-indicators">
                <button type="button" data-bs-target="#carouselExample" data-bs-slide-to="0" class="active"
                    aria-current="true"></button>
                <button type="button" data-bs-target="#carouselExample" data-bs-slide-to="1"></button>
                <button type="button" data-bs-target="#carouselExample" data-bs-slide-to="2"></button>
                <button type="button" data-bs-target="#carouselExample" data-bs-slide-to="3"></button>
                <button type="button" data-bs-target="#carouselExample" data-bs-slide-to="4"></button>
            </div>
            <div class="carousel-inner ">
                <div class="carousel-item active">
                    <img src="" class="d-block mx-auto img-fluid" alt="Interior">
                </div>
                <div class="carousel-item">
                    <img src="" class="d-block mx-auto img-fluid" alt="Producto 1">
                </div>
                <div class="carousel-item ">
                    <img src="" class="d-block mx-auto img-fluid" alt="Producto 2">
                </div>
                <div class="carousel-item ">
                    <img src="" class="d-block mx-auto img-fluid" alt="Product 3">
                </div>
                <div class="carousel-item ">
                    <img src="" class="d-block mx-auto img-fluid" alt="Fachada">
                </div>
            </div>

            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Previous</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Next</span>
            </button>
        </div>
    </div>
</template>