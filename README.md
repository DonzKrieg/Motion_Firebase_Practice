Week 8 - Firebase

Firebase adalah platform pengembangan aplikasi dari Google yang mana menyediakan berbagai layanan seperti penyimpanan data, autentikasi, analisis, dan lainnya.
Firebase ini cocok digunakan dalam pengembangan aplikasi Flutter untuk mengintegrasikan fitur-fitur backend dengan cepat dan efisien.

Firestore adalah salah satu layanan cloud database dari Firebase. Firestore memungkinkan menyimpan dan mengelola data aplikasi secara mudah.
Perubahan data dilakukan secara realtime yang disinkronkan secara otomatis di semua perangkat yang terhubung.
Firestore juga mendukung pengembangan aplikasi berbagai platform.

Collection adalah sekumpulan document dalam Firestore.
Mirip dengan tabel dalam database relasional, Collection memungkinkan Anda untuk menyimpan dan mengelola sekelompok data terkait dalam aplikasi anda.

Document adalah tempat di mana Anda menyimpan data didalam Firestore. Setiap document memiliki kumpulan data yang berisi informasi. Setiap document memiliki ID yang unik untuk membedakan satu dengan yang lainnya.

Stream merupakan Asynchronous Function yang dikirimkan secara berurutan berdasarkan event yang diberikan.
Berbeda dengan Future yang hanya mengembalikan satu data saja. Seperti aliran air, Stream akan selalu mengembalikan data sampai tidak ada lagi data yang melewati aliran tersebut.

StreamBuilder (widget) merupakan Widget yang berperan untuk mendengarkan sebuah event dari stream
Stream builder di-build berdasarkan snapshot terbaru yang didapatkan dari interaksi dengan stream.

Snapshot adalah data yang dikembalikan oleh stream dan ditangkap oleh listener
Stream builder akan selalu build ulang ketika terdapat perbaruan snapshot
