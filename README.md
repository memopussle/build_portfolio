# Stock Portfolio

## Goals: 

#### 1. Create a simple component layout
#### 2. Populate the output with some initial data
#### 3. Calculate market value based on market price and shares owned
#### 4. Calculate unrealized gain/loss based on market value, cost per share, and shares owned
#### 5. Calculate the portfolio total market value, and unrealized gain/loss
#### 6. Add JavaScript to the remove button to delete a stock from the list
#### 7. Make shares owned, cost per share, and market price editable
#### 8. Allow user to add a new stock to the portfolio

## Steps:
1. Create a simple component with the layout ( Heading element and a table structure)

2. Populate the out put with some initial data

- Use state component to store some initial data

- Render input elements, assign its values to variable stored in state component to update it

3. Calculate market value and Unrealised gain/loss ,assign it to input elements

4. Total market value and gain/loss -> insert it in JSX

5. Remove stock : target portfolio object ( in this.state). each stock is represented as an object. To remove a single stock, we just have to remove the corresponding object from the array.

6. Make the input elements editable: add event handler to input elements and bind it to this.state