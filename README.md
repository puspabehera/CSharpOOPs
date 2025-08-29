# CSharpOOPs
OOPS


Encapsulation
```
public class BankAccount
{
    // Private field: not accessible directly from outside
    private decimal balance;

    // Public method to deposit amount
    public void Deposit(decimal amount)
    {
        if (amount > 0)
            balance += amount;
    }

    // Public method to get the balance
    public decimal GetBalance()
    {
        return balance;
    }
}

```
