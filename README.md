# Tugas_Evaluasi_Determinan_Dan_invers

## Nama: Yogi Dwi Ramadani
## NIM: 250411100198
## Mata Kuliah: Komputasi Aljabar Linier

## A. Determinan Matriks (Ekspansi Baris)

Rumus

Determinannya:

det(A) = Σ (-1)^(i+k) * a_ik * M_ik

## Soal 1 (Matriks 2×2)

A = | -7  -5 |
    |  1   4 |

Perhitungan:

det(A) = (-7)(4) - (-5)(1)
       = -28 + 5
       = -23

Hasil:

det(A) = -23

## Soal 2 (Matriks 3×3)

A = | 0   2  -3 |
    | 1  -2  -1 |
    | 0   0   1 |

Ekspansi Baris Pertama:

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

Perhitungan:

(Menggunakan ekspansi baris atau reduksi baris)

Hasil:

det(A) = -256
