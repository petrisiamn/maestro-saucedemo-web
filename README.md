# 🧪 poc-maestro-studio

> **Maestro Studio** automation testing PoC with **GitHub Actions CI/CD** — targeting [SauceDemo](https://www.saucedemo.com).

---

## 📚 Tech Stack

| Technology | Purpose |
|---|---|
| [Maestro Studio](https://maestro.dev/) | Automation framework |
| [TBD]() | Test reporting |
| [GitHub Actions](https://github.com/features/actions) | CI/CD pipeline |


## 📁 Project Structure

```
maestro-saucedemo-web/
├── .github/workflows/
│   └── maestro.yml                 # GitHub Actions CI/CD pipeline
├── flow/
│   ├── e2e/                        # all scenario and common step
│   └── subflow/                    # reusable script (js) to support e2e scenario
├── congig                          
├── assets                    
└── README.md                       # This file
```

## 🔐 Environment Variables

to do


## 🚀 Getting Started


### Installation

https://docs.maestro.dev/get-started/quickstart

### Running Tests

```bash
# Run all tests
# maestro test path/filescenario.yml
maestro test flow/e2e/checkout_products.yaml
```
