# DynamicForm

Fungsi ini akan menampilkan propinsi sesuai dengan negara yang dipilih, kota sesuai dengan propinsi yang dipilih, kecamatan sesuai kota yang dipilih, dan kelurahan sesuai kecamatan yang dipilih.

Untuk menggunakan fungsi ini, cukup dengan memanggil fungsi untuk menginisialisasi negara saja. Selanjutnya elemen dihubungkan dengan cara menentukan selector dari atribut elemet di atasnya.

Atribut Select

1. data-url
2. data-value
3. data-bind-children
4. data-children-selector

data-url berisi URL dari data untuk elemen tersebut.

data-value berisi nilai dari elemen saat ini. Hal ini disebabkan karena elemen select tidak harus berisi option

data-bind-children berisi nilai "true" atau "false". Jika diisi dengan "true", maka ketika elemen ini selesai diinisialisasi atau ketika nilai elemen ini diubah dengan event "change", elemen children akan diinisialisasi kembali dengan menggunakan nilai terakhir dari elemen ini.

data-children-selector adalah selector dari elemen children. Selector dapat berupa tag, id, class, atribut, dan pseudoclass.
