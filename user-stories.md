The design for this project is found in the /design folder.

Here are some rough user stories for you to work to:

Basket-001
As a user
I want to view my current basket
So that I can see what I've added

Given I am on the basket page
When I view the page
Then I can see all added items and their cost

Basket-002
As a user
I want to change the quantity of a basket item
So that I can decide item totals before purchasing

Given I am on the basket page
When I view the page
Then I can see an item quantity next to each item

Given I am on the basket page
When I view the page
Then I can see each item's total cost (adjusted for quantity)

Given I am on the basket page
When I change an item quantity
Then the item's total cost is adjusted, in real-time

Basket-003
As a user
I want to view my current basket total
So that I can see what I'm going to have to pay

Given I am on the basket page
When I view the page
Then I can see a total cost, accounting for all items and quantities

Basket-004
As a user
I want to remove all items from my basket
So that I can start over

Given I am on the basket page
When I click the "clear" button
Then all items are reset to zero (but remain in the basket)
