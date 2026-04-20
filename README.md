# Tugas Determinan Dan invers

## Nama: Yogi Dwi Ramadani
## NIM: 250411100198
## Mata Kuliah: Komputasi Aljabar Linier

## A. Hitunglah determinan matrik berikut dengan menggunakan rumus expansi baris

Rumus Determinannya =
det(A) = Σ (-1)^(i+k) * a_ik * M_ik

Rumus Minor =
M_ij = det A_ij

## Soal 1 (Matriks 2×2)

A = | -7  -5 |
    |  1   4 |

det(A) = (-7)(4) - (-5)(1)
       = -28 + 5
       = -23
Hasil:
det(A) = -23

## Soal 2 (Matriks 3×3)

A = | 0   2  -3 |
    | 1  -2  -1 |
    | 0   0   1 |

Ekspansi Baris:
det(A) = 0·M11 - 2·M12 + (-3)·M13

Minor:
M12 = | 1  -1 |
      | 0   1 | = (1)(1) - (-1)(0) = 1

M13 = | 1  -2 |
      | 0   0 | = (1)(0) - (-2)(0) = 0

Perhitungan:
det(A) = 0 - 2(1) + (-3)(0)
       = -2
Hasil:
det(A) = -2

## Soal 3 (Matriks 4×4)

A = |  1  -3   1   1 |
    | -3   1   1   1 |
    |  1   1  -3   1 |
    |  1   1   1  -3 |

det(A) = 1·M11 - (-3)·M12 + 1·M13 - 1·M14
       = 1·M11 + 3·M12 + 1·M13 - 1·M14

Minor M11
Hapus baris 1 kolom 1:

M11 = |  1   1   1 |
      |  1  -3   1 |
      |  1   1  -3 |

det(M11) = 1((-3)(-3) - (1)(1))
         - 1((1)(-3) - (1)(1))
         + 1((1)(1) - (-3)(1))

         = 1(9 - 1)
         - 1(-3 - 1)
         + 1(1 + 3)

         = 8 + 4 + 4
         = 16

Minor M12
Hapus baris 1 kolom 2:

M12 = | -3   1   1 |
      |  1  -3   1 |
      |  1   1  -3 |

det(M12) = -3((−3)(−3) − (1)(1))
         - 1((1)(−3) − (1)(1))
         + 1((1)(1) − (−3)(1))

         = -3(9 - 1)
         - 1(-3 - 1)
         + 1(1 + 3)

         = -24 + 4 + 4
         = -16

Minor M13
Hapus baris 1 kolom 3:

M13 = | -3   1   1 |
      |  1   1   1 |
      |  1   1  -3 |

det(M13) = -3((1)(-3) - (1)(1))
         - 1((1)(-3) - (1)(1))
         + 1((1)(1) - (1)(1))

         = -3(-3 - 1)
         - 1(-3 - 1)
         + 1(1 - 1)

         = 12 + 4 + 0
         = 16

Minor M14
Hapus baris 1 kolom 4:

M14 = | -3   1   1 |
      |  1   1  -3 |
      |  1   1   1 |

det(M14) = -3((1)(1) - (-3)(1))
         - 1((1)(1) - (-3)(1))
         + 1((1)(1) - (1)(1))

         = -3(1 + 3)
         - 1(1 + 3)
         + 1(1 - 1)

         = -12 - 4 + 0
         = -16

Substitusi ke Rumus
det(A) = 1(16) + 3(-16) + 1(16) - 1(-16)
       = 16 - 48 + 16 + 16
       = 0
       
Hasil Akhir :
det(A) = 0

## B. Gunakan rumus matriks adjoin untuk menghitung invers dari matriks berikut dengan rumus

Rumus adjoin =
(adj A)_ij = (-1)*i+jM_ji

Rumus Invers =
A*-1 = 1/det A _ adj A

## Soal 1
A = \begin{bmatrix} -7 & -5 \\ 1 & 4 \end{bmatrix}
