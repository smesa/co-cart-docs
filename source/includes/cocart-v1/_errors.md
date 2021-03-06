# Error Responses #

<img src="images/github.svg" width="20" height="20" alt="GitHub Mark Logo"> [Edit on GitHub](https://github.com/co-cart/co-cart-docs/blob/master/source/includes/cocart-v1/_errors.md)

You might encounter an error when using CoCart. These error responses explain what might have happened.

| Error Status | Error Response |
| ------------ | -------------- |
| `cocart_cannot_read_cart` | Cannot read cart! |
| `cocart_customer_missing` | Customer ID is required! |
| `cocart_clear_cart_failed` | Clearing the cart failed! |
| `cocart_product_id_required` | Product ID number is required! |
| `cocart_product_id_not_numeric` | Product ID must be numeric! |
| `cocart_quantity_not_numeric` | Quantity must be numeric! |
| `cocart_product_does_not_exist` | Warning: This product does not exist! |
| `cocart_product_sold_individually` | You cannot add another "%s" to your cart. <i class="label label-info">%s is the product name</i> |
| `cocart_cannot_be_purchased` | Sorry, this product cannot be purchased. |
| `cocart_product_out_of_stock` | You cannot add &quot;%s&quot; to the cart because the product is out of stock. <i class="label label-info">%s is the product name</i> |
| `cocart_not_enough_in_stock` | You cannot add a quantity of %1$s for "%2$s" to the cart because there is not enough stock. - only %3$s remaining! <i class="label label-info">%1$s is the quantity requested, %2$s is the product name. %3$s is the stock remaining.</i> |
| `cocart_not_enough_stock_remaining` | You cannot add that amount to the cart &mdash; we have %1$s in stock and you already have %2$s in your cart. |
| `cocart_cannot_add_to_cart` | You cannot add "%s" to your cart. <i class="label label-info">%s is the product name</i> |
| `cocart_can_not_remove_item` | Unable to remove item from cart. |
| `cocart_can_not_restore_item` | Unable to restore item to the cart. |
| `cocart_can_not_update_item` | Unable to update item quantity in cart. |
| `cocart_cart_item_key_required` | Cart item key is required! |
| `cocart_no_items` | No items in cart. |
| `cocart_item_not_in_cart` | Item specified does not exist in cart. |