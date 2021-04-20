# Grafana Flame Graph

Flame graphs are a visualization of profiled software, allowing the most frequent code-paths to be identified quickly and accurately. This Grafana Data Source Backend Plugin allows to visualize frequent code-paths over time. 

## Getting started

A data source backend plugin consists of both frontend and backend components.
To build both on dev mode you can simply:

```bash
git clone https://github.com/codeperfio/grafana-flame-graph
cd grafana-flame-graph
yarn start:dev
```

To stop dev mode you can simply:

```bash
yarn stop:dev
```

### Frontend

1. Install dependencies

```bash
yarn install
```

2. Build plugin in development mode or run in watch mode

```bash
yarn dev
```

or

```bash
yarn watch
```

3. Build plugin in production mode

```bash
yarn build
```

### Backend

1. Build backend plugin binaries for Linux:

```bash
yarn build:backend
```

2. List all available Mage targets for additional commands:

```bash
mage -l
```
