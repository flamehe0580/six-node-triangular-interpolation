# six-node-triangular-interpolation

The key coefficient arrays for constructing Hermite-Lagrange interpolation basis.

`Hermite-T16.dat` stores the array of:

N = transpose(φ) * inverse(transpose([Φ, ∂Φ/∂ξ, ∂Φ/∂η]))

其中：
- N: 插值基函数系数数组
- φ: 基函数向量  
- Φ: Hermite插值条件矩阵
- ∂Φ/∂ξ, ∂Φ/∂η: Φ对ξ和η的偏导数矩阵
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
