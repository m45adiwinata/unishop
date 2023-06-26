<template>
    <nav class="navbar navbar-expand-lg fixed-top light-color">
        <div class="container-fluid">
            <a class="navbar-brand" href="#"><h1 class="" id="header-logo">ESCAPER<sup style="font-size:40%; vertical-align:top; top:7px;">&#174;</sup></h1></a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0" id="navbar-menu">
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                            SHOP
                        </a>
                        <ul class="dropdown-menu invis-bg">
                            <li><a class="dropdown-item" href="#">T-SHIRTS</a></li>
                            <li><a class="dropdown-item" href="#">SWEATSHIRTS</a></li>
                            <li><a class="dropdown-item" href="#">HATS</a></li>
                            <li><a class="dropdown-item" href="#">JACKETS</a></li>
                            <li><a class="dropdown-item" href="#">PRINTS</a></li>
                        </ul>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">LOOKBOOK</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">ABOUT</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">CONTACT</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
</template>
<style scoped>
@media screen and (min-width: 992px) {
    #navbar-menu {
        position: fixed;
        right: 10%;
    }
}
.light-color a {
    color: white;
} 
</style>