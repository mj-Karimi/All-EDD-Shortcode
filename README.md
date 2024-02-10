# All-EDD-Shortcode
Easy Digital Download All Shortcode
 Sample way to show Basket Card:

 ```
<?php if (edd_get_cart_quantity()): ?>
		<div class="alert alert-success text-center" role="alert">
<a class="me-3 py-2 text-dark text-decoration-none" href="/checkout">
  <span type="button" class="btn btn-outline-success"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-cart-fill" viewBox="0 0 16 16">
  <path d="M0 1.5A.5.5 0 0 1 .5 1H2a.5.5 0 0 1 .485.379L2.89 3H14.5a.5.5 0 0 1 .491.592l-1.5 8A.5.5 0 0 1 13 12H4a.5.5 0 0 1-.491-.408L2.01 3.607 1.61 2H.5a.5.5 0 0 1-.5-.5M5 12a2 2 0 1 0 0 4 2 2 0 0 0 0-4m7 0a2 2 0 1 0 0 4 2 2 0 0 0 0-4m-7 1a1 1 0 1 1 0 2 1 1 0 0 1 0-2m7 0a1 1 0 1 1 0 2 1 1 0 0 1 0-2"/>
</svg> Cart Total: <span class="badge bg-secondary"><?php echo edd_get_cart_quantity(); ?> Item - <?php echo edd_get_cart_total();?>$</span> 
</span></a>

</div><?php endif; ?>
```
