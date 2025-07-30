### 📘 **Compound Interest Calculator**

This is one of my first Java projects — a simple **console-based application** that calculates the future value of an investment using the **compound interest formula**:

$$
A = P \left(1 + \frac{r}{n} \right)^{nt}
$$


🔗 Formula ↔ Code Mapping

| Formula Component | Description                                     | Java Variable     |
| ----------------- | ----------------------------------------------- | ----------------- |
| `A`               | Final amount after time `t`                     | `amount`          |
| `P`               | Principal amount                                | `principal`       |
| `r`               | Annual interest rate (in decimal)               | `rates`           |
| `n`               | Number of times interest is compounded per year | `timesCompounded` |
| `t`               | Time in years                                   | `years`           |


### 🚀 Why This Project?

I'm currently learning Java, and this project helped me understand:

* User input via `Scanner`
* Basic arithmetic operations
* Using `Math.pow()` for exponential calculations
* Formatting output using `System.out.printf()`

### 🔹 Features

* Interactive user input
* Accurate compound interest calculation
* Clean and readable console output

### 🛠️ Tech Stack

* Java (JDK 8+)
* Console application

### 💡 Sample Run

```
Enter the principal amount: 10000
Enter the interest rates (in %): 5
Enter the number of times compounded per year: 4
Enter the number of years: 10
The amount after 10 years is $16470.09
```

🧑‍💻 Created by: Vivek Bhatt