# Statistics HW

Interactive assignments for a statistics course, built around security and
cryptography topics. Each one is a single self-contained HTML page: plain
JavaScript and inline SVG charts, no external libraries.

| File | Topic |
|------|-------|
| `HMWK_1` | **Private key to public key on a toy elliptic curve.** Scalar multiplication on y² = x³ + 7 (mod 17), point addition, double-and-add, and statistics of the resulting points (distribution, bits, correlation, avalanche effect). Compares a one-way function with a hash. |
| `HMWK_2` | **From wallet seed to Ethereum address.** The full BIP-39, BIP-32, BIP-44, secp256k1, Keccak-256 and EIP-55 chain computed in the browser, with the differences between generation, derivation, hashing, checksum and encoding. Includes Keccak vs SHA-3. |
| `HMWK_2A` | **Encryption and cryptanalysis: toy ECC vs Caesar.** The same message encrypted with both schemes, then attacked: letter-frequency analysis on Caesar (χ², bigrams, dictionary) and exhaustive search and baby-step giant-step on the restricted private key. |
| `HMWK_3` | **Aggregate scores: law of large numbers and central limit theorem.** m attackers against n systems under Bernoulli and Rademacher models. Sₙ, Sₙ/n and Sₙ/√n studied through trajectories, histograms, variances, and convergence in probability and in distribution. |
| `HMWK_4` | **Welford recurrences and sample statistics.** Derivation of the recursive formulas for mean, sum of squares and variance, with a numerical stability test; sample means and variances of m hackers on n systems compared with μ and σ² as n grows. |
| `HMWK_5` | **Riemann and Lebesgue integration, and the normal CDF.** Numerical integrals of nine functions with both approaches, including the Dirichlet and Thomae functions; Φ(x) computed with six methods (trapezoid, Simpson, series, erf approximations). |

To try one, download the file and open it in a browser.
