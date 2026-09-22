User enters an order
        |
     Validate
        |
    Check stocks
        |
       Router 
  |                 |
  In stock       Out of stock
  |                 |
  Confirmed       Rejected
          |
          END


State:
1. Information that is provided by user: product (str), qty(int)
2. Information updated by validation and stock: is_valid(bool), router(bool)
3. Status of the order: str