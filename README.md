# QFTools

QFTools is a Python package designed for quantitative finance. It is ideal for quants, risk managers, and anyone working in quantitative finance who needs an easy-to-use and powerful set of tools to perform complex financial calculations.

## Features

## Installation

You can clone the repository and install it manually:

```bash
git clone https://github.com/Panadaren/QFTools.git
cd QFTools
poetry install
```

This will install all dependencies defined in the `pyproject.toml` file and set up a virtual environment for you.

## Basic Usage

After installation, you can start using QFTools for your quantitative finance tasks. Below is an example of using QFTools to calculate the price of a European call option using the Black-Scholes model:

## Development Setup

To contribute to QFTools or run the development version, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Panadaren/QFTools.git
   cd QFTools
   ```

2. **Install dependencies using Poetry:**

   ```bash
   poetry install
   ```

   This will install the required dependencies and set up the development environment.

3. **Activate the virtual environment:**

   ```bash
   poetry shell
   ```

   This will activate the virtual environment managed by Poetry.

4. **Run tests and make changes:**

   You can run tests or make changes to the package. Poetry will manage all dependencies for you.

   ```bash
   pytest
   ```

### Code Formatting and Linting

This project enforces style consistency using flake8, black, and isort. It is recommended to run these tools before committing your code:

   ```bash
   poetry run isort .
   poetry run black .
   poetry run flake8
   ```

## Contributing

We welcome contributions to QFTools! If you'd like to contribute, please fork the repository and submit a pull request. For reporting issues or suggesting new features, feel free to open an issue on GitHub.

### Steps to Contribute

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request.

## License

QFTools is licensed under the MIT License. See [LICENSE](LICENSE) for more details.