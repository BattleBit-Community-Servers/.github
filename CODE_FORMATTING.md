# Code Formatting Guidelines

Welcome to BattleBit Community Servers! We greatly appreciate your interest in contributing to our projects. To ensure the consistency, readability, and maintainability of our codebase, please adhere to these comprehensive code formatting guidelines when submitting code changes.

## Table of Contents

- [Code Formatting Guidelines](#code-formatting-guidelines)
  - [Table of Contents](#table-of-contents)
  - [General Guidelines](#general-guidelines)
  - [Indentation](#indentation)
  - [Naming Conventions](#naming-conventions)
  - [Comments](#comments)
  - [Spacing](#spacing)
  - [Line Length](#line-length)
  - [Imports](#imports)
  - [Examples](#examples)
  
## General Guidelines

- **Clean, Readable, Maintainable Code**: Strive for code that is not only functional but also clean and easy to read and maintain.
- **Consistency is Key**: Maintain consistency with the coding style and conventions used throughout the project. Consistency aids collaboration and readability.
- **Respect for Existing Code**: Show respect for the existing codebase; adhere to the established practices and patterns.

## Indentation

- **Use 4 Spaces**: Indent code blocks using 4 spaces for each level of indentation. Avoid using tabs.
- **Consistency**: Maintain consistent indentation throughout the entire codebase.

## Naming Conventions

- **Descriptive and Meaningful Names**: Use descriptive and meaningful variable, function, and class names.
- **CamelCase**: Utilize camelCase for variable and function names (e.g., `myVariable`, `calculateTotalPrice()`).
- **PascalCase**: Employ PascalCase for class names (e.g., `MyClass`).
- **Avoid Single-letter Variables**: Unless they represent iterators in loops, avoid single-letter variable names (e.g., `i`, `j`, `k`).
- **Language-specific Conventions**: Follow language-specific naming conventions if applicable (e.g., PEP 8 for Python, PSR-2 for PHP).

## Comments

- **Explain Complexity**: Add comments to elucidate complex or non-obvious sections of code.
- **Avoid Over-commenting**: Use inline comments sparingly; prioritize writing self-explanatory code over excessive comments.
- **Document Public Interfaces**: Thoroughly document public functions and classes, including descriptions of their purpose, parameters, and return values.
- **Keep Comments Updated**: Ensure comments are kept up-to-date with code changes.

## Spacing

- **Spaces After Commas and Operators**: Add a single space after commas and operators (e.g., `a = 1 + 2`, not `a=1+2`).
- **Logical Separation**: Use a single empty line to logically separate different blocks of code.
- **Remove Trailing Whitespaces**: Eliminate trailing white spaces at the end of lines.
- **Consistent Spacing**: Maintain consistent spacing within code constructs (e.g., if statements, loops).

## Line Length

- **Reasonable Line Length**: Keep lines of code reasonably short, typically under 80-120 characters.
- **Split Long Lines**: Break long lines into multiple lines when necessary to enhance readability.

## Imports

- **Organized Import Statements**: Organize import statements clearly and consistently.
- **Use Relative Imports**: Prefer relative imports when specifying the module's location.
- **Avoid Unnecessary Imports**: Refrain from importing unnecessary modules, promoting efficiency.

## Examples

**Python Example**:
```python
# Good example
def calculate_total_price(item_price, quantity):
    """
    Calculate the total price of an item.

    Args:
        item_price (float): The price of the item.
        quantity (int): The quantity of the item.

    Returns:
        float: The total price.
    """
    total_price = item_price * quantity
    return total_price


# Bad example
def calcPrice(ip, qty):
    total = ip * qty
    return total
```
**C# Example**:
```csharp
// Good example
public class ShoppingCart
{
    public decimal CalculateTotalPrice(decimal itemPrice, int quantity)
    {
        // Calculate the total price.
        decimal total = itemPrice * quantity;
        return total;
    }
}


// Bad example
public class ShoppingCart
{
    public decimal calcPrice(decimal ip, int qty)
    {
        decimal total = ip * qty;
        return total;
    }
}
```

These comprehensive guidelines aim to maintain code quality and consistency across our projects. Following these standards will contribute to a smoother contribution and review process for all contributors. Your commitment to improving BattleBit Community Servers is highly appreciated! Thank you for your valuable contributions.