# Modul [03] - [Trigonometri]

**Nama:** [Anisa Dwi Lestari]  
**NIM:** [1306625005]  
**Kelas:** [Fisika c]  

---

## 1. Problem Statement
> Membuat program untuk menghitung sin dan cos dengan pendekatan deret Mc Laurin.

## 2. Mathematical Equation
      a. Deret McLaurin untuk Sinus:
          $$\sin x = \sum_{n=0}^{\infty} \frac{(-1)^n \, x^{2n+1}}{(2n+1)!}$$
          $$\sin x = x - \frac{x^3}{3!} + \frac{x^5}{5!} - \frac{x^7}{7!} + \cdots$$
      b.Deret McLaurin untuk Cos:
      $$\cos x = \sum_{n=0}^{\infty} \frac{(-1)^n \, x^{2n}}{(2n)!}$$
$$\cos x = 1 - \frac{x^2}{2!} + \frac{x^4}{4!} - \frac{x^6}{6!} + \cdots$$
      C. Rumus Relative Error
      $$E_r = \left| \frac{x_{\text{approx}} - x_{\text{true}}}{x_{\text{true}}} \right|$$
$$E_r = \left| \frac{x_{\text{approx}} - x_{\text{true}}}{x_{\text{true}}} \right| \times 100\%$$
## 3. Algorithm
> Tuliskan langkah-langkah logika penyelesaian masalah secara sistematis sebelum diimplementasikan ke dalam kode Python (`main.py`).
