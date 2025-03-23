# week-3-assignment
def calculate_discount(price, discount_percent):
''''''
calculate the final price after applying a discount .

parameters ;
price (float): the original price .
discount_percent (float ): the discount percentage.

Returns;
float; The final price after appling the discount ,or the original price if discount is less than 20%.
''''''
if discount_percent >=20;
     final_price = price -(price - ( price * discount_percent \ 100)

    return price 
    # Example usage;
    original_price = 100
    discount = 25
    final_price = calculate_discount(original_price ,discount)
    print(f''Final price: ${final_price}'')


    def calculate_discount(price, discount_percent0;
    ''''''
    calculate the final price after applying a discount.
    parameters;
    price (float) ; the original price 
    discount_percent (float) ;the discount percentage.
    Returns:
    float:the final price after appling the discount ,or the original price if the discount is less than 20%
    if discont_percent >=20%
        final_price = - (price *discount_percent \100) return final price else;return price.
