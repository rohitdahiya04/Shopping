# Shopping Cart Calculator

A simple command-line Shopping Cart Calculator written in Python. Users can add items, enter their prices, and calculate the total cost of all items in the cart.

## Features

* Add multiple food items to a shopping cart.
* Enter custom prices for each item.
* Automatically calculates the total bill.
* Displays all purchased items.
* Easy-to-use command-line interface.

## Requirements

* Python 3.x

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/rohitdahiya04/shopping-cart-calculator.git
```

2. Navigate to the project directory:

```bash
cd shopping-cart-calculator
```

3. Run the program:

```bash
python main.py
```

## How to Use

1. Enter the name of a food item.
2. Enter its price when prompted.
3. Continue adding items to your cart.
4. Enter `q` when you are finished.
5. The program will display:

   * All items in the cart
   * Total cost of the purchase

## Example

```text
Enter a food to buy (q to quit): Pizza
Enter the price of a Pizza: $12

Enter a food to buy (q to quit): Burger
Enter the price of a Burger: $8

Enter a food to buy (q to quit): Coke
Enter the price of a Coke: $2

Enter a food to buy (q to quit): q

-----YOUR CART-----
Pizza | Burger | Coke |

Your total is: $22.0
```

## Project Structure

```text
shopping-cart-calculator/
│
├── main.py
└── README.md
```

## Future Improvements

* Display item prices alongside item names.
* Support item quantities.
* Remove items from the cart.
* Generate a formatted receipt.
* Save purchase history to a file.

## Skills Demonstrated

* Python Lists
* Loops (`while`, `for`)
* User Input Handling
* Basic Arithmetic Operations
* Data Storage and Processing

## Author

Rohit Dahiya

* GitHub: https://github.com/rohitdahiya04

## License

This project is open source and available under the MIT License.
