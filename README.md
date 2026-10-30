# IRIS Programming Language 👁️

> Inspired by Eye. Build For Code

IRIS is a lightweight, intuitive, and modern programming language designed for fast development with built-in web automation and native capabilities. 

## Key Features
- **Built-in Web Automation:** Perform HTTP requests natively using `web.get[...]` and `web.open[...]` powered by libcurl.
- **Clean Syntax:** Minimalist and expressive design inspired by modern development workflows (`let`, `const`, `var`).
- **Developer Friendly:** Human-readable output commands like `say` and `print`.

## Quick Start / Syntax Examples

IRIS 1.0 syntax:
age {15}

if{age >= 13}
    say{"Access granted"}
elseif{age >= 10}
    say{"Limited access"}
else
    say{"Access denied"}
end

## Installation & Requirements
IRIS currently runs on Windows (x64) and requires `libcurl-4.dll` to be present in the same directory for web features.

1. Download the latest release from the Releases tab.
2. Run `iris.exe` to enter the Interactive REPL mode.
3. Or run a file: `iris.exe script.iris`

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
