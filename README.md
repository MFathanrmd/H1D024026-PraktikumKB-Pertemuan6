# H1D024026-PraktikumKB-Pertemuan6

## Jaringan Syaraf Tiruan (JST)

| Informasi | Detail |
|-----------|--------|
| **Nama** | Muhammad Fathan Ramdani |
| **NIM** | H1D024026 |
| **Shift Awal** | A |
| **Shift Akhir** | B |
| **Pertemuan** | 6 - Jaringan Syaraf Tiruan (JST) |

## Deskripsi

Praktikum ini membahas konsep Jaringan Syaraf Tiruan (JST) dan metode pembelajarannya, serta menerapkannya dalam kode Python. Terdapat dua studi kasus yang dikerjakan:

### 1. Masalah OR dengan Perceptron
Implementasi model Perceptron untuk menyelesaikan masalah logika OR dengan data bipolar.

- **Input & Target**: Bipolar (-1, 1)
- **Learning Rate**: 0.1
- **Max Epoch**: 10
- **Fungsi Aktivasi**: Bipolar (step function)

**File terkait:**
- `Perceptron.py` — Kelas model Perceptron
- `Perceptron_or.py` — Script utama untuk menjalankan model
- `HasilPerceptron.txt` — Output hasil perhitungan

### 2. Masalah XOR dengan Backpropagation
Implementasi model Backpropagation (multi-layer neural network) untuk menyelesaikan masalah logika XOR yang tidak bisa diselesaikan oleh Perceptron single-layer.

- **Input & Target**: Bipolar (-1, 1)
- **Learning Rate**: 0.3
- **Max Epoch**: 1000
- **Target Error (SSE)**: 0.001
- **Fungsi Aktivasi**: Sigmoid Bipolar (tanh)
- **Arsitektur**: 2 input → 2 hidden → 1 output

**File terkait:**
- `Backpropagation.py` — Kelas model Backpropagation
- `Backpropagation_xor.py` — Script utama untuk menjalankan model
- `hasilBackpropagation.txt` — Output hasil perhitungan

## Cara Menjalankan

```bash
# Install dependencies
pip install numpy matplotlib

# Jalankan Perceptron (masalah OR)
python Perceptron_or.py

# Jalankan Backpropagation (masalah XOR)
python Backpropagation_xor.py
```

## Dependencies

- Python 3.x
- NumPy
- Matplotlib
