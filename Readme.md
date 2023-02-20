# Magento Custom Theme (New Theme)
## Create Custom Topbar
To create a Custom topbar in frontend, Please follow the below steps

## 1. Create Block
Follow below settings,

Enable Block -> Yes, Block Title -> Custom Topbar, Identifier -> custom-top-header, Store View -> All Store Views

#### Edit with Page Builder (HTML Code)
```
<div class="custom-topbar">
  <div class="container">
    <ul>
       <li><a href="#">My Account</a></li>
       <li><a href="#">Wishlist</a></li>
       <li><a href="#">My Cart</a></li>
       <li><a href="#">Checkout</a></li>
       <li><a href="#">Login</a></li>
    </ul>
  </div>
</div>
```
## 2. Create Widget
Follow below settings,

#### Storefront Properties
Type -> CMS Static Block, Design Package/Theme -> New Theme, Widget Title -> Custom Topbar Widget Assign to Store Views -> All Store Views, Sort Order -> 0, Display On -> All Pages, Container -> Page Top

#### Widget Option
Block -> Custom Topbar

## Create Client Logo Block
## 1. Create Block
Follow below settings,

Enable Block -> Yes, Block Title -> Client Logo, Identifier -> client-logo, Store View -> All Store Views

#### Edit with Page Builder (HTML Code)

```
<div class="client-logos">
  <div class="logos">
    <img src="{{media url=wysiwyg/Client-logos/client-logo.png}}" alt="" />
  </div>
  <div class="logos">
      <img src="{{media url=wysiwyg/Client-logos/client-logo.png}}" alt="" />
    </div>
  <div class="logos">
      <img src="{{media url=wysiwyg/Client-logos/client-logo.png}}" alt="" />
    </div>
  <div class="logos">
      <img src="{{media url=wysiwyg/Client-logos/client-logo.png}}" alt="" />
    </div>
  <div class="logos">
      <img src="{{media url=wysiwyg/Client-logos/client-logo.png}}" alt="" />
    </div>
  <div class="logos">
      <img src="{{media url=wysiwyg/Client-logos/client-logo.png}}" alt="" />
    </div>
  <div class="logos">
      <img src="{{media url=wysiwyg/Client-logos/client-logo.png}}" alt="" />
    </div>
  <div class="logos">
      <img src="{{media url=wysiwyg/Client-logos/client-logo.png}}" alt="" />
    </div>
  <div class="logos">
      <img src="{{media url=wysiwyg/Client-logos/client-logo.png}}" alt="" />
    </div>
  <div class="logos">
      <img src="{{media url=wysiwyg/Client-logos/client-logo.png}}" alt="" />
    </div>
  <div class="logos">
      <img src="{{media url=wysiwyg/Client-logos/client-logo.png}}" alt="" />
    </div>
  <div class="logos">
      <img src="{{media url=wysiwyg/Client-logos/client-logo.png}}" alt="" />
  </div>
</div>
          <script>
                requirejs( [ 'require', 'jquery', 'js/slick' ],
                    function( require, $, slick ) {
                        $('.client-logos').slick({
                            infinite: true,
                            speed: 300,
                            slidesToShow: 7,
                            prevArrow: $('.prev-slide'),
                            nextArrow: $('.next-slide'),
                            autoplay: true,
                            slidesToScroll: 1,
                           responsive: [
                                {
                                    breakpoint: 1024,
                                    settings: {
                                        slidesToShow: 2,
                                        slidesToScroll: 1
                                    }
                                },
                                {
                                    breakpoint: 600,
                                    settings: {
                                        slidesToShow: 2,
                                        slidesToScroll: 2
                                    }
                                },
                                {
                                    breakpoint: 480,
                                    settings: {
                                        slidesToShow: 2,
                                        slidesToScroll: 2
                                    }
                                }
                            ]
                        });
                    });
            </script>
```
## 2. Create Widget
Follow below settings,

#### Storefront Properties
Type -> CMS Static Block, Design Package/Theme -> New Theme, Widget Title -> Client Logo Widget Assign to Store Views -> All Store Views, Sort Order -> 0, Display On -> All Pages, Container -> Before Page Footer

#### Widget Option
Block -> Client Logo


## Create Custom Footer

## 1. Create Block
Follow below settings,

Enable Block -> Yes, Block Title -> Custom Footer, Identifier -> custom-footer, Store View -> All Store Views

#### Edit with Page Builder (HTML Code)
(Please use the image attached in Images section)

```
<div class="footer">
   <div class="footer-column column-one">
      <img src="{{media url=wysiwyg/Client-logos/logo_1_.png}}" alt="" />
       <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s</p>
       <p class="footer-address"><i class="fab fa-telegram"></i> 0123 Main Road, Your City, NY 123456</p>
       <p class="footer-number"><i class="fa fa-phone"></i> (000) 2345 - 6789</p>
       <p class="footer-address"><i class="fa fa-envelope"></i> info@marketsupply.com</p>
   </div>
   <div class="footer-column column-two">
     <h3 class="footer-title">Information</h3>
        <ul class="footer links">
           <li class="nav item"><a href="{{store url="about-us"}}">About us</a></li>
           <li class="nav item"><a href="{{store url="customer-service"}}">Customer Service</a></li>
        </ul>
   </div>
   <div class="footer-column column-three">
     <h3 class="footer-title">Our Social</h3>
       <a href="#" class="social-icons facebook"><i class="fab fa-facebook-f"></i> Facebook</a>
       <a href="#" class="social-icons twitter"><i class="fab fa-twitter"></i> Twitter</a>
       <a href="#" class="social-icons instagram"><i class="fab fa-instagram"></i> Instagram</a>
       <a href="#" class="social-icons youtube"><i class="fab fa-youtube"></i> Youtube</a>
       <a href="#" class="social-icons google"><i class="fab fa-google-plus-g"></i> Google +</a>
   </div>
   <div class="footer-column column-four">
     <h3 class="footer-title">Opening Time</h3>
     <p class="opening-time"> <i class="fas fa-solid fa-clock"></i> Monday - Friday:08:30 am - 09:30pm <br>Sat - Sun: 09:00am - 10:00pm</p>
     <h3 class="footer-title">Payment Option</h3>
<img src="{{media url=wysiwyg/Client-logos/payment-option.png}}" alt="" />
   </div>
</div>
```
## 2. Create Widget
Follow below settings,

#### Storefront Properties
Type -> CMS Static Block, Design Package/Theme -> New Theme, Widget Title -> Custom Footer Widget Assign to Store Views -> All Store Views, Sort Order -> 0, Display On -> All Pages, Container -> Page Footer

#### Widget Option
Block -> Custom Footer Widget

