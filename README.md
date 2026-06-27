🚢 MarineOps-Engine

A specialized Revenue Operations (RevOps) and automation extension for ERPNext tailored for the maritime and marine logistics sector. This application serves as a central hub to optimize sales pipelines, automate multi-currency vessel billing, track conversion metrics via SQL, and expose webhooks for seamless n8n integration.

### Installation

You can install this app using the [bench](https://github.com/frappe/bench) CLI:

```bash
cd $PATH_TO_YOUR_BENCH
bench get-app $URL_OF_THIS_REPO --branch develop
bench install-app kailas_app
```

### Contributing

This app uses `pre-commit` for code formatting and linting. Please [install pre-commit](https://pre-commit.com/#installation) and enable it for this repository:

```bash
cd apps/kailas_app
pre-commit install
```

Pre-commit is configured to use the following tools for checking and formatting your code:

- ruff
- eslint
- prettier
- pyupgrade

### License

mit
