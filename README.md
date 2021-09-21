# Praktikum5 - Bagian II
## Pengantar
Praktikum5 Bagian II adalah lanjutan dari praktikum 5 yang telah anda kerjakan sebelumnya. 
Jika pada Praktikum 5 bagian 1, anda menulis ulang kode program yang disediakan dan mengeksekusi program, maka pada bagian II ini anda diminta untuk mengimplementasikan kelas diagram yang diberikan menggunakan template source yang telah disediakan.
Diharapkan anda sudah memahami kelas diagram, alur program, konsep inheritance, overloading dan overriding pada praktikum 5 bagian II.


## Petunjuk Praktikum

#### Modul 2 **[Poin 70]** Kelas Shape dan turunannya serta ShapeDriver
>File-file berikut ini bisa anda temukan di folder **src\main\java\praktikum4**.

Lengkapi program Shape.java, Circle.java, Rectangle.java sesuai dengan kelas diagram berikut.
![Image of Soal2](http://api.puro.del.ac.id/v1/file/1a67003e6dac5fc3cb2976e7e8641a12)
Kelas Shape lengkapi dengan konstruktor dengan parameter, setter dan getter. Sementara untuk Circle dan Rectangle lengkapi dengan konstruktor, kopi konstruktor, setter, dan getter.

* Konstruktor tanpa parameter pada Cirlcle akan membentuk objek Circle dengan posisi titik tengah (0,0) dan diameter 1.
* Konstruktor tanpa parameter pada Rectangle akan membentuk objek Rectangle dengan posisi (0,0) dan (0,0).
* Setiap konstruktor pada Circle dan Rectangle memberi nama objek Circle atau Rectangle secara langsung bukan dari variabel parameter konstruktor.
* Method getArea() : untuk menghitung luas Circle atau Rectangle.
* Method getCircle() : untuk menghitung keliling Circle atau Rectangle.
	
Modul 2 ini dilengkapi dengan sejumlah test sebagai berikut:
* ***TestShape.testKonstrukturDenganParameter*** akan menguji konstruktor dengan parameter pada kelas Shape.
* ***TestShape.testSetName*** akan menguji setter pada kelas Shape.

* ***TestCircle.testKonstruktorI*** akan menguji konstruktor tanpa parameter pada kelas Circle.
* ***TestCircle.testKonstruktorII*** akan menguji konstruktor dengan parameter pada kelas Circle.
* ***TestCircle.testKopiKonstruktor*** akan menguji kopi konstruktor pada kelas Circle.
* ***TestCircle.testSetter*** akan menguji setter pada kelas Circle.
* ***TestCircle.testSetDiameter*** akan menguji method setDiameter() pada kelas Circle.
* ***TestCircle.testGetArea*** akan menguji method getArea() pada kelas Circle.
* ***TestCircle.testGetKeliling*** akan menguji method getCircumference() pada kelas Circle.
* ***TestCircle.testToString*** akan menguji method toString() pada kelas Circle.

* ***TestRectangle.testKonstruktorI*** akan menguji konstruktor tanpa parameter pada kelas Rectangle.
* ***TestRectangle.testKonstruktorII*** akan menguji konstruktor dengan parameter pada kelas Rectangle.
* ***TestRectangle.testKopiKonstruktor*** akan menguji kopi konstruktor pada kelas Rectangle.
* ***TestRectangle.testSetter*** akan menguji setter pada kelas Rectangle.
* ***TestRectangle.tesGetWidth*** akan menguji method getWidth() pada kelas Rectangle.
* ***TestRectangle.testGetHeight*** akan menguji method getHeight() pada kelas Rectangle.
* ***TestRectangle.testGetArea*** akan menguji method getArea() pada kelas Rectangle.
* ***TestRectangle.testGetKeliling*** akan menguji method getCircumference() pada kelas Rectangle.
* ***TestRectangle.testToString*** akan menguji method toString() pada kelas Rectangle.
* ***TestShapeDriver.testCreateRectangle*** akan menguji method createRectangle() pada kelas ShapeDriver yang akan menginstasiasi kelas Rectangle menggunakan konstruktor dengan parameter.
* ***TestShapeDriver.testCreateCircle*** akan menguji method createCircle() pada kelas ShapeDriver yang akan menginstasiasi kelas Circle menggunakan konstruktor dengan parameter.

Contoh keluaran dari Modul 2 (ShapeDriver.java) adalah sebagai berikut:
![Image of Soal2](http://api.puro.del.ac.id/v1/file/c574cd8813db9cf404c405927a73d5fc)


	
 


**Catatan Penting:**
1. Anda hanya boleh mengubah kode program yang ada di src\main\java
1. **Semua kode program yang ada di src\test\java  tidak boleh diubah sama sekali!!** Jika anda ubah (akan terlihat pada history), maka nilai anda langsung 0.
1. Jangan memindah-mindahkan file, biarkan setiap file di folder di mana file tersebut berada sebelumnya.
1. Pada beberapa template program sudah disediakan method yang tidak boleh diubah. Maka jangan anda ubah!
