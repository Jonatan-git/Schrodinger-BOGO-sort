# Schrodinger-BOGO-sort
Inspirasi dari teori kucing Schrödinger dan sorting absurd ala Bogo Sort. Algoritma dalam superposisi: mungkin sorted, mungkin tidak — sampai kamu cek.
# 🧪 Schrödinger BOGO Sort

> _"Array ini berada dalam superposisi antara 'udah urut' dan 'belum urut' — sampai kamu liat."_

---

## 🎯 Deskripsi

**Schrödinger BOGO Sort** adalah algoritma sorting parodi yang menggabungkan:

- **Bogo Sort**: Sorting paling absurd, mengacak hingga hasilnya urut.
- **Kucing Schrödinger**: Objek dalam dua keadaan sekaligus sampai diamati.

➡️ Array akan terus diacak dalam **keadaan superposisi** antara “sudah urut” dan “belum urut”, dan hanya akan “collapse” ke salah satu kenyataan saat kamu mengecek hasilnya.

---

## 🧪 Contoh Pemakaian

```python
from schrodinger_bogo_sort import schrodinger_bogo_sort

arr = [5, 2, 4, 1]
sorted_arr = schrodinger_bogo_sort(arr)
print(\"Sorted array:\", sorted_arr)
