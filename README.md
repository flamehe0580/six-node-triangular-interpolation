# six-node-triangular-interpolation

The key coefficient arrays for constructing Hermite-Lagrange interpolation basis.

`Hermite-T16.dat` stores the array of:

```
N = transpose(φ) * inverse(transpose([Φ, ∂Φ/∂ξ, ∂Φ/∂η]))
```

Where:
- **N**: The coefficient array of interpolation basis functions
- **φ**: The vector of basis functions  
- **Φ**: The Hermite interpolation condition matrix
- **∂Φ/∂ξ**, **∂Φ/∂η**: The partial derivative matrices of Φ with respect to ξ and η coordinates

---

**Alternative notation (using Unicode subscripts):**
```
𝐍 = 𝛟ᵀ [𝚽  𝚽_ξ  𝚽_η]⁻ᵀ
```
