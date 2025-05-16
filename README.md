# Binomial_Option_Pricing

Overview:

This notebook implements the Binomial Option Pricing Model, a fundamental numerical method for valuing options.
The model discretizes the price movements of the underlying asset and back-calculates option values through a risk-neutral probability framework.
The implementation includes:
  - Loop-Based Method – Traditional iterative approach for pedagogical clarity.
  - Vectorized Method – Uses NumPy for efficient matrix operations
    
Features:
  Computes option price for European Call/Put options
  Allows user-defined steps (N) to refine accuracy
  Plots the convergence of Tree to Black-Scholes model

References
- Hull, J.C. (Options, Futures, and Other Derivatives)
- Cox, Ross, & Rubinstein (Binomial Option Pricing Model)




