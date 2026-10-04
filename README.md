# options-engine

A Python library for pricing European and American options with three methods
(Black-Scholes closed form, binomial tree, Monte Carlo), computing the Greeks,
backing out implied volatility, and building an implied volatility smile from
real market data.

**Status:** in progress (Week 1: Black-Scholes core)

## Planned features
- Black-Scholes price and analytic Greeks
- Implied volatility solver
- Binomial (CRR) tree, European and American
- Monte Carlo pricer with variance reduction
- Implied volatility smile from a real option chain

## Setup
```bash
git clone https://github.com/YOUR-USERNAME/options-engine.git
cd options-engine
python -m venv .venv
source .venv/Scripts/activate   # Mac/Linux: source .venv/bin/activate
pip install -e ".[dev]"
pytest
```

## Author
Yashas
