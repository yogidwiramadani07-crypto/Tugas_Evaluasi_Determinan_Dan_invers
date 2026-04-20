# Tugas Determinan Dan invers

## Nama: Yogi Dwi Ramadani
## NIM: 250411100198
## Mata Kuliah: Komputasi Aljabar Linier

### A. Hitunglah determinan matrik berikut dengan menggunakan rumus expansi baris

Rumus Determinannya =
det(A) = Σ (-1)^(i+k) * a_ik * M_ik

Rumus Minor =
M_ij = det A_ij

#### Soal 1

A = | -7  -5 |
    |  1   4 |

Hitung Minor :
M11 = 4
M12 = 1

Subtitusikan :
det(A)=(−1)*2(−7)(4)+(−1)*3(−5)(1)
=(1)(−7)(4)+(−1)(−5)(1)
=−28+5
=−23

det(A)=−23
Jadi, determinan matriks A adalah −23.

#### Soal 2

A = | 0   2  -3 |
    | 1  -2  -1 |
    | 0   0   1 |

Hitung Minor :
M12 = (1)(1)−(0)(−1)=1
M13 = (1)(0)−(0)(−2)=0

Subtitusikan :
det(A)=(−1)*3(2)(1)+(−1)*4(−3)(0)
=(−1)(2)(1)+(1)(−3)(0)
=−2+0=−2

det(A) = -2
jadi determinan dari matriks A adalah -2.

#### Soal 3

A = |  1  -3   1   1 |
    | -3   1   1   1 |
    |  1   1  -3   1 |
    |  1   1   1  -3 |

det(A) = 1·M11 - (-3)·M12 + 1·M13 - 1·M14
       = 1·M11 + 3·M12 + 1·M13 - 1·M14

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

Substitusikan :
det(A) = 1(16) + 3(-16) + 1(16) - 1(-16)
       = 16 - 48 + 16 + 16
       = 0

det(A) = 0
jadi determinan dari matriks A adalah 0

## B. Gunakan rumus matriks adjoin untuk menghitung invers dari matriks berikut dengan rumus

Rumus adjoin =
(adj A)_ij = (-1)*i+jM_ji

Rumus Invers =
A*-1 = 1/det A _ adj A

## Soal 1
A = | -7  -5 |
    |  1   4 |

Hitung Adjoin :
adj(A)= |  4  5 |
        | -1 -7 |
        
Hitung Determinan :
det(A)=(−7)(4)−(−5)(1)=−28+5=−23

Hitung Invers :
A*-1 = 1/-23 |  4  5 |
             | -1 -7 |
A*-1 = | -4/23  5/23 |
       | -1/23 -7/23 |

## Soal 2
A = | 0   2  -3 |
    | 1  -2  -1 |
    | 0   0   1 |

Hitung Determinan :
det(A)=−2

Hitung Adjoin :
adj(A)= | -2  -2  8  |
        | -1   0  3  |
        |  0   0  -2 |
        
Hitung Invers :
A*-1 = 1/-2  | -2  -2  8  |
             | -1   0  3  |
             |  0   0  -2 |
A*-1 = | 1     1   -4    |
       | 1/2   0   -3/2  |
       |  0    0    1    |

## Soal 3
A = |  1  -3   1   1 |
    | -3   1   1   1 |
    |  1   1  -3   1 |
    |  1   1   1  -3 |

Hitung Determinan :
det(A)= -256

Hitung Adjoin :
adj(A)= | -2  -2  8  |
        | -1   0  3  |
        |  0   0  -2 |
        
Hitung Invers :
A*-1 = 1/-2  | -2  -2  8  |
             | -1   0  3  |
             |  0   0  -2 |
A*-1 = | 1     1   -4    |
       | 1/2   0   -3/2  |
       |  0    0    1    |
