<script>
  export default {
    data() {
      return {
        product_1: {
          title: 'Air Jordan 4 Retro SE - Black Canvas',
          price: 300,
          imageLink: '@/assets/images/gallery_1.jpg',
          imageAlt: 'Image Yeezy Boost 700'
        }
      }
    },
  }
</script>

<template>
      <nav class="navbar">
        <input type="checkbox" id="check" class="checkbox">
        <div class="hamburger-menu">
            <label for="check" class="menu">
                <div class="menu-line menu-line-1"></div>
                <div class="menu-line menu-line-2"></div>
                <div class="menu-line menu-line-3"></div>
            </label>
        </div>
        <div class="navbar-navigation">
            <div class="navbar-navigation-left">
                <img src="@/assets/images/nav-img-1.jpg" alt="navigation image" class="left-img left-img-1">
                <img src="@/assets/images/nav-img-2.jpg" alt="navigation image" class="left-img left-img-2">
                <img src="@/assets/images/nav-img-3.jpg" alt="navigation image" class="left-img left-img-3">
            </div>
            <div class="navbar-navigation-right">
                <ul class="nav-list">
                    <li class="nav-list-item">
                        <a href="#" class="nav-list-link">Home</a>
                    </li>
                    <li class="nav-list-item">
                        <a href="#" class="nav-list-link">Products</a>
                    </li>
                    <li class="nav-list-item">
                        <a href="#" class="nav-list-link">Cart</a>
                    </li>
                    <li class="nav-list-item">
                        <a href="#" class="nav-list-link">About us</a>
                    </li>
                    <li class="nav-list-item">
                        <a href="#" class="nav-list-link">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
    <header class="header">
        <div class="brand">
            <a href="#" class="logo">
                <i class="fas fa-shoe-prints"></i>
            </a>
            <div>
                <h1 class="main-name">Snaky Sneakers</h1>
                <p class="sub-name">Sneaker Reseller</p>
            </div>
        </div>
        <div class="header-banner">
            <h1 class="main-heading">Welcome</h1>
            <h3 class="sub-heading">Find you preferred sneakers now</h3>
            <button type="button" class="main-button">Buy now</button>
        </div>
    </header>
    <section class="about">
        <div class="about-left">
            <img src="@/assets/images/team.jpg" alt="Picture of our team">
        </div>
        <div class="about-right">
            <h1 class="main-heading">Our team</h1>
            <h3 class="sub-heading">Only for the best sneaker experience</h3>
            <div class="stars">
                <i class="fas fa-star-of-life star"></i>
                <i class="fas fa-star-of-life star"></i>
                <i class="fas fa-star-of-life star"></i>
            </div>
            <p class="description">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Soluta alias voluptas error quam commodi minima adipisci est. Ipsa exercitationem assumenda repellendus nemo debitis dolorum sunt at alias et, nulla iste beatae rerum similique architecto explicabo ullam a quaerat commodi! Vitae odit architecto commodi natus tempora consequuntur repudiandae temporibus laudantium placeat.</p>
            <div class="stars">
                <i class="fas fa-star-of-life star"></i>
                <i class="fas fa-star-of-life star"></i>
                <i class="fas fa-star-of-life star"></i>
            </div>
            <button class="main-button" type="button">Read more</button>
        </div>
    </section>
    <section class="gallery">
        <div class="cards-wrapper">
            <div class="card">
                <div class="card-overlay">
                  
                    <h1 class="card-overlay-heading">{{ product_1.title }}</h1>

                    <p class="card-overlay-paragraph">Price: €300</p>
                    <button class="card-overlay-button">Order now</button>
                </div>
                <img src="@/assets/images/gallery_1.jpg" alt="Image Yeezy Boost 700" class="card-image">
            </div>
            <div class="card">
                <div class="card-overlay">
                    <h1 class="card-overlay-heading">Air Jordan 4 Retro SE - Black Canvas</h1>
                    <p class="card-overlay-paragraph">Price: €280</p>
                    <button class="card-overlay-button">Order now</button>
                </div>
                <img src="@/assets/images/gallery_2.jpg" alt="Image Air Jordan 4 Retro SE" class="card-image">
            </div>
            <div class="card">
                <div class="card-overlay">
                    <h1 class="card-overlay-heading">Wtaps X Authentic Syndicate - Wings</h1>
                    <p class="card-overlay-paragraph">Price: €125</p>
                    <button class="card-overlay-button">Order now</button>
                </div>
                <img src="@/assets/images/gallery_3.jpg" alt="Wtaps X Authentic Syndicate" class="card-image">
            </div>
            <div class="card">
                <div class="card-overlay">
                    <h1 class="card-overlay-heading">Undefeated X Zoom Kobe 1 ProTro - White Gum</h1>
                    <p class="card-overlay-paragraph">Price: €625</p>
                    <button class="card-overlay-button">Order now</button>
                </div>
                <img src="@/assets/images/gallery_4.jpg" alt="Image Undefeated X Zoom Kobe 1 ProTro" class="card-image">
            </div>
            <div class="card">
                <div class="card-overlay">
                    <h1 class="card-overlay-heading">Air Jordan 4 Retro - Red Thunder</h1>
                    <p class="card-overlay-paragraph">Price: €360</p>
                    <button class="card-overlay-button">Order now</button>
                </div>
                <img src="@/assets/images/gallery_5.jpg" alt="Image Air Jordan 4 Retro" class="card-image">
            </div>
            <div class="card">
                <div class="card-overlay">
                    <h1 class="card-overlay-heading">Off-White X Air Force 1 Low - Brooklyn</h1>
                    <p class="card-overlay-paragraph">Price: €1325</p>
                    <button class="card-overlay-button">Order now</button>
                </div>
                <img src="@/assets/images/gallery_6.jpg" alt="Image Off-White X Air Force 1 Low" class="card-image">
            </div>
        </div>
    </section>
    <footer class="footer">
        <div class="footer-header">
            <a href="#" class="logo">
                <i class="fas fa-shoe-prints"></i>
            </a>
            <div>
                <h1 class="main-name">Snaky Sneakers</h1>
                <p class="sub-name">Sneaker reseller</p>
            </div>
        </div>
        <div class="footer-social-media">
            <ul class="social-media">
                <li class="social-media-item">
                    <a href="#" class="social-media-link">
                        <i class="fab fa-facebook-square"></i>
                    </a>
                </li>
                <li class="social-media-item">
                    <a href="#" class="social-media-link">
                        <i class="fab fa-instagram"></i>
                    </a>
                </li>
                <li class="social-media-item">
                    <a href="#" class="social-media-link">
                        <i class="fab fa-youtube"></i>
                    </a>
                </li>
                <li class="social-media-item">
                    <a href="#" class="social-media-link">
                        <i class="fab fa-snapchat"></i>
                    </a>
                </li>
            </ul>
        </div>
        <div class="footer-copyright">
            <p class="footer-copyright-paragraph">&copy; Copyright. Snaky Sneakers. All rights reserved</p>
        </div>
    </footer>
</template>

<style>
</style>
