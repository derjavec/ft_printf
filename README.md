## Welcome to ft_printf Function Overview!

### Understanding va_list:

The `va_list` is a crucial tool for handling variable arguments in C. It allows functions to accept a variable number of arguments, making them flexible and powerful.

### How It Works:

Our ft_printf function serves as a comprehensive alternative to the standard printf function. It takes a format string and a variable number of arguments, then processes them according to the provided format specifications.

### Options Explained:

- **`%c`:** Prints a single character.
- **`%s`:** Prints a string.
- **`%p`:** Prints a memory address in hexadecimal format.
- **`%d`, `%i`:** Prints decimal numbers.
- **`%u`:** Prints unsigned decimal numbers.
- **`%x`:** Prints numbers in lowercase hexadecimal format.
- **`%X`:** Prints numbers in uppercase hexadecimal format.
- **`%%`:** Prints a percent sign.

These options closely mimic the behavior of printf(), providing users with familiar functionality.

---

In my code:
- The `ft_format` function is responsible for interpreting each format specifier and handling the corresponding conversion.
- `ft_printf` orchestrates the entire process by looping through the format string and invoking `ft_format` as needed.

Explore ft_printf, and discover a powerful tool for formatted printing in C!
