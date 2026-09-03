# ecommerce-search-algorithm
A Python program that searches e-commerce products based on category, price, and rating using a Linear Search and Sequential Filtering algorithm.
# E-Commerce Search Algorithm

## Description

A Python program that searches e-commerce products based on category, price, and rating using **Linear Search and Sequential Filtering**.

---

## Scenario

An online shopping website allows users to search products using:

- Product Name
- Price
- Category
- Rating

The program filters products based on the user's search requirements.

---

## Computational Thinking

### Decomposition

The main problem is divided into smaller tasks:

- Search products
- Check category
- Check price
- Check rating
- Display matching products

### Abstraction

Only important product information is used:

- Name
- Price
- Category
- Rating

### Pattern Recognition

Different search operations have different patterns:

- Name → Text Search
- Category → Exact Matching
- Price → Range Search
- Rating → Range Filtering
- Multiple conditions → Multi-Filter Search

---

## Algorithm

The program uses **Linear Search with Sequential Filtering**.

### Steps

1. Go through each product.
2. Check whether the category matches.
3. Check whether the price is within the required range.
4. Check whether the rating meets the requirement.
5. Add matching products to the results.
6. Display the final results.

---

## Example Search

Category = Electronics
Maximum Price = 70000
Minimum Rating = 4.5



