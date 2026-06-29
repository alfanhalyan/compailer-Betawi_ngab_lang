## Struktur Direktori

```text
betawi-ngab-lang/
│
├── docs/
│   ├── language_design.md
│   ├── grammar.md
│   └── symbol_table.md
│
├── compiler/
│   ├── lexer.py
│   ├── parser.py
│   ├── ast_nodes.py
│   ├── semantic.py
│   ├── optimizer.py
│   ├── codegen.py
│   └── main.py
│
├── examples/
│   ├── contoh.btw
│   └── sample_program.btw
│
├── output/
│   ├── generated_code.py
│   └── result.txt
│
├── assets/
│   └── logo.png
│
├── requirements.txt
├── .gitignore
└── README.md
```

## Spesifikasi Bahasa BETA

### Kata Kunci (Keywords) & Operator

Bahasa BETA memetakan instruksi pemrograman ke dalam Bahasa Betawi Tangerang:

- `kudu` : Deklarasi variabel (wajib)

- `kalo` : Kondisional `if`

- `selaen` : Kondisional `else`

- `selagi` : Perulangan `while`

- `ngomong(...)` : Menampilkan output ke terminal (`print`)

- `tanya(...)` : Meminta input pengguna (`input`)

- `jadi_angka(...)` : Konversi ke tipe angka (`int` / `float`)

- `jadi_tulisan(...)` : Konversi ke tipe string (`str`)

- `bener` : Nilai boolean `True`

- `salah` : Nilai boolean `False`
