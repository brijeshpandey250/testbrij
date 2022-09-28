<template>
    <!-- header -->
    <header>
        <div class="container">
            <div class="header d-lg-flex justify-content-between align-items-center">
                <div class="header-agile">
                    <h1>
                        <router-link to="/" class="navbar-brand logo">
                        <span class="fa fa-scissors" aria-hidden="true"></span> Men spa <span
                        class="fa fa-user-secret" aria-hidden="true"></span>
                        </router-link>
                    </h1>
                </div>
                <div class="nav_w3ls">
                    <nav>
                        <label for="drop" class="toggle mt-lg-0 mt-1"><span class="fa fa-bars"
                                aria-hidden="true"></span></label>
                        <input type="checkbox" id="drop" />
                        <ul class="menu">
                            <li class="mr-lg-3 mr-2 active">
                                <router-link to="/" class="top-bar-link">
                                    <span>Home</span>
                                </router-link>
                            </li>
                            <li class="mr-lg-3 mr-2 ">
                                <router-link to="/about" class="top-bar-link">
                                    <span>About</span>
                                </router-link>
                            </li>
                            <li class="mr-lg-3 mr-2">
                                <router-link to="/" class="top-bar-link">
                                    <span>Gallery</span>
                                </router-link>
                            </li>
                            <li class="mr-lg-3 mr-2">
                                <router-link to="/" class="top-bar-link">
                                    <span>Contact Us</span>
                                </router-link>
                            </li>
                        </ul>
                    </nav>
                </div>

            </div>
        </div>
    </header>
    <!-- //header -->

    <RouterView />

    <!-- footer -->
    <footer class="footer-content">
        <div class="layer footer">
            <div class="container-fluid">
                <div class="row footer-top-inner-w3ls">
                    <div class="col-lg-4 col-md-6 footer-top ">
                        <h2>
                            <router-link to="/">
                            Men Spa </router-link>
                        </h2>
                        <p class="my-3">Donec consequat sam libero tempore, cum soluta nobis est eligendi optio cumque
                            nihil impedit quo minus</p>
                        <p>
                            Id quod possimusapien ut leo cursus rhoncus. Nullam dui mi, vulputate ac metus at, semper
                            varius orci.
                        </p>
                    </div>
                    <div class="col-lg-4 col-md-6 mt-md-0 mt-5">
                        <div class="footer-w3pvt">
                            <h3 class="mb-3 w3pvt_title">Opening Hours</h3>
                            <hr>
                            <ul class="list-info-w3pvt last-w3ls-contact mt-lg-4">
                                <li>
                                    <p> Monday - Friday 08.00 am - 10.00 pm</p>

                                </li>
                                <li class="my-2">
                                    <p>Saturday 08.00 am - 10.00 pm</p>

                                </li>
                                <li class="my-2">
                                    <p>Sunday 08.00 am - 10.00 pm</p>

                                </li>


                            </ul>
                        </div>
                    </div>
                    <div class="col-lg-3 col-md-6 mt-lg-0 mt-5">
                        <div class="footer-w3pvt">
                            <h3 class="mb-3 w3pvt_title">Contact Us</h3>
                            <hr>
                            <div class="last-w3ls-contact">
                                <p>
                                    <a href="mailto:example@email.com">info@example.com</a>
                                </p>
                            </div>
                            <div class="last-w3ls-contact my-2">
                                <p>+ 456 123 7890</p>
                            </div>
                            <div class="last-w3ls-contact">
                                <p>+ 90 nsequursu dsdesdc,
                                    <br>xxx Honey State 049436.
                                </p>
                            </div>
                        </div>
                    </div>

                </div>

                <p class="copy-right-grids text-li text-center my-sm-4 my-4">© 2022 Men spa. All Rights Reserved
                </p>
                <div class="w3ls-footer text-center mt-4">
                    <ul class="list-unstyled w3ls-icons">
                        <li>
                            <a href="#">
                                <span class="fa fa-facebook-f"></span>
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                <span class="fa fa-twitter"></span>
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                <span class="fa fa-dribbble"></span>
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                <span class="fa fa-vk"></span>
                            </a>
                        </li>
                    </ul>
                </div>
                <div class="move-top text-right"><a href="#home" class="move-top"> <span class="fa fa-angle-up  mb-3"
                            aria-hidden="true"></span></a></div>
            </div>
            <!-- //footer bottom -->
        </div>
    </footer>
    <!-- //footer -->



</template>

