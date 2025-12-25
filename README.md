# six-node-triangular-interpolation

The key coefficient arrays for constructing Hermite-Lagrange interpolation basis.

---
`Hermite-T16.dat` and `Hermite-T32.dat` store the arrays of:</br>
𝐍 = 𝛟ᵀ [𝚽  𝚽<sub>ξ</sub>  𝚽<sub>η</sub>]⁻ᵀ</br>
where:
- 𝐍: The coefficient array of interpolation basis functions
- 𝛟: The vector of basis functions  
- 𝚽: The Hermite interpolation condition matrix
- 𝚽<sub>ξ</sub>, 𝚽<sub>η</sub>: The partial derivative matrices of Φ with respect to ξ and η coordinates

`Hermite-T16.dat` and `Hermite-T32.dat` consist of floating-point numbers with 16 and 32 significant digits of precision, respectively.

---
`Lagrange-T16.dat` and `Lagrange-T32.dat` store the arrays of:</br>
𝐍 = 𝛟ᵀ𝚽⁻ᵀ</br>
where:
- 𝐍: The coefficient array of interpolation basis functions
- 𝛟: The vector of basis functions  
- 𝚽: The Hermite interpolation condition matrix

`Lagrange-T16.dat` and `Lagrange-T32.dat` consist of floating-point numbers with 16 and 32 significant digits of precision, respectively.
