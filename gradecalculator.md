# Dokumentasi Testing Logika GradeMate

## Testing
---
**Test Case 1 : Menghitung Nilai Akhir Normal (Lulus)**

INPUT :

Nilai UTS = 80

Nilai UAS = 85

Nilai Tugas = 90

Nilai Kuis = 75

Expected Output:  
Nilai Akhir: 82,5

Status: Lulus

Actual Output: 

Nilai Akhir: 82,5

Status: Lulus

**Status**: PASS   

---
**Test Case 2 : Menghitung Nilai Akhir Batas Minimum**

INPUT :

Nilai UTS = 40

Nilai UAS = 50

Nilai Tugas = 60

Nilai Kuis = 30

Expected Output:  
Nilai Akhir: 45

Status: Tidak Lulus

Actual Output: 

Nilai Akhir: 45

Status: Tidak Lulus

**Status**: PASS

---

**Test Case 3: Input Nilai Tidak Valid**

INPUT :

Nilai UTS = 120

Nilai UAS = 80

Nilai Tugas = -10

Nilai Kuis = 90

Expected Output:  

Input salah! Nilai harus berada dalam rentang 0 - 100.   

Input diminta ulang.

Actual Output:   

Input salah! Nilai harus berada dalam rentang 0 - 100.   

Input diminta ulang.   

**Status**: PASS  






  
