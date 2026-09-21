# Dokumentasi Testing Logika Grade Mahasiswa


```javascript
const { hitungGrade } = require('./gradeCalculator');

describe('Pengujian Perhitungan Nilai Akhir & Grade', () => {

  // Test 1: Grade A
  test('harus mengembalikan Grade A jika Nilai Akhir >= 80', () => {
    const result = hitungGrade(85, 85, 80, 80);
    expect(result.nilaiAkhir).toBe(82);
    expect(result.grade).toBe('A');
  });

  // Test 2: Grade B
  test('harus mengembalikan Grade B jika Nilai Akhir di rentang 70 - 79', () => {
    const result = hitungGrade(70, 70, 75, 75);
    expect(result.nilaiAkhir).toBe(73);
    expect(result.grade).toBe('B');
  });

  // Test 3: Grade C
  test('harus mengembalikan Grade C jika Nilai Akhir di rentang 60 - 69', () => {
    const result = hitungGrade(60, 60, 65, 65);
    expect(result.nilaiAkhir).toBe(63);
    expect(result.grade).toBe('C');
  });

});


  
