variable laundry
variable red_basket
variable white_basket
variable delicate_basket
variable other_basket

for each cloth in laundry
- if red move to red_basket
- else if white move to white_basket
- else if delicate move to delicate_basket
- else move to other_basket

variable baskets = red_basket, white_basket, delicate_basket, other_basket

for each basket in baskets
- Put the basket of clothes in the machine
- Add laundry soap to the machine.
- if delicate_basket Apply the machine settings.
- Turn the machine on and wait until it's done.
- Remove the laundry and return it to the basket.
