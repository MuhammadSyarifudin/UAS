# Apa itu Class ?
class adalah mekanisme yang digunakan untuk membuat struktur data pengguna baru yang ditentukan. Ini berisi data serta metode yang digunakan untuk memproses data tersebut.
# Apa itu Instance ?
Instance adalah salinan *class* dengan nilai sebenarnya , secara harfiah merupakan objek *class* tertentu.
# Apa hubungan Class dan Instance ?
Sementara *class* adalah cetak biru yang digunakan untuk menggambarkan bagaimana membuat sesuatu, instance adalah objek yang dibuat dari cetak biru tersebut.
# Apa syntax Phython yang digunakan untuk menentukan Class baru ?
#### *class* Python*class*Name:
# Apa konvensi ejaan untuk nama class?
CamelCase notasi, dimulai dengan huruf kapital — yaitu,
#### Python*class*Name()
# Bagaimana Anda memberi instantiate, atau membuat instance dari, sebuah class?
Anda menggunakan nama class, diikuti dengan tanda kurung. Jadi jika nama classnya *Karyawan*(), contoh Karyawannya adalah - my_class = *Karyawan*()
# Bagaimana Anda mengakses atribut dan perilaku instance class ?
Dengan notasi titik — misalnya, instance_name.attribute_name
# Apa itu metode ?
Sebuah fungsi yang didefinisikan di dalam class
# Apa tujuannya self ?
Argumen pertama dari setiap metode merujuk pada instance class saat ini, yang menurut konvensi, diberi nama self. Dalam __init__metode ini, selfmengacu pada objek yang baru dibuat; sementara dalam metode lain, selfmengacu pada contoh yang metode namanya disebut. Untuk lebih lanjut tentang __init__vs self, lihat artikel ini .
# Apa tujuan dari __init__metode ini ?
__init__Metode menginisialisasi sebuah instance dari class.