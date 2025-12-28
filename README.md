# Finance Plugins

A Claude Code plugin marketplace for financial analysis and trading.

## Installation

```bash
# Add the marketplace
/plugin marketplace add ferdousbhai/finance-plugins

# Install plugins
/plugin install investor@finance-plugins   # Market data & research
/plugin install tasty@finance-plugins      # TastyTrade brokerage
/plugin install alpaca@finance-plugins     # Alpaca Markets
```

## Plugins

| Plugin | Description | Source |
|--------|-------------|--------|
| `investor` | Market data, sentiment, earnings, stock research | [investor-agent](https://github.com/ferdousbhai/investor-agent) |
| `tasty` | TastyTrade brokerage integration | [tasty-agent](https://github.com/ferdousbhai/tasty-agent) |
| `alpaca` | Alpaca Markets trading API | [alpaca-mcp-server](https://github.com/alpacahq/alpaca-mcp-server) |

## Configuration

### Alpaca

Set environment variables for Alpaca API access:
```bash
export ALPACA_API_KEY="your-key"
export ALPACA_API_SECRET="your-secret"
```

### TastyTrade

See [tasty-agent README](https://github.com/ferdousbhai/tasty-agent) for authentication setup.

## License

MIT
