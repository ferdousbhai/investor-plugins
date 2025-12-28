# Investor Plugins

A Claude Code plugin marketplace for financial analysis and trading.

## Installation

```bash
# Add the marketplace
/plugin marketplace add ferdousbhai/investor-plugins

# Install plugins
/plugin install investor@investor-plugins   # Market data & research
/plugin install tasty@investor-plugins      # TastyTrade brokerage
/plugin install alpaca@investor-plugins     # Alpaca Markets
/plugin install ibkr@investor-plugins       # Interactive Brokers
```

## Plugins

| Plugin | Description | Source |
|--------|-------------|--------|
| `investor` | Market data, sentiment, earnings, stock research | [investor-agent](https://github.com/ferdousbhai/investor-agent) |
| `tasty` | TastyTrade brokerage integration | [tasty-agent](https://github.com/ferdousbhai/tasty-agent) |
| `alpaca` | Alpaca Markets trading API | [alpaca-mcp-server](https://github.com/alpacahq/alpaca-mcp-server) |
| `ibkr` | Interactive Brokers trading | [interactive-brokers-mcp](https://github.com/code-rabi/interactive-brokers-mcp) |

## Configuration

### Alpaca

```bash
export ALPACA_API_KEY="your-key"
export ALPACA_API_SECRET="your-secret"
```

### Interactive Brokers

Requires Node.js 18+. On first run, browser opens for OAuth authentication.

### TastyTrade

See [tasty-agent README](https://github.com/ferdousbhai/tasty-agent) for authentication setup.

## License

MIT
