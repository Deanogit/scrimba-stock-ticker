## Stock Ticker App

### Scrimba BackEnd JavaScript Challenge

A small challenge to practice `.setInterval()`, `object destructuring`, `import/export`, `ternary operators`, `Date()`, `Math()`.

#### `.setInterval()`

We use `.setInterval()` to repeatedly call the `renderStockTicker()` function every 1500 milliseconds.

    - This function call checks the `prevPrice` to conditionally render the `priceIconElement` green if `price` it is greater than the `prevPrice`, red if `price` is smaller than `prevPrice` or grey if equal.

    - `.getElementById` is used to manipulate the DOM in the `index.html`, getting the `stockData` from `getStockData()` in the `fakeStockAPI.js` file.

    - Each time `getStockData()` is called inside the `setInterval()` the function call generates a new random number between 0 and 3 to two decimal places. It also generates a new Date object, which is rendered as a string by using `.toLocaleSTimetring()`
