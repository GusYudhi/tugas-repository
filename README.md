# Cara Meggoreng Telur


```c
procedure goreng_telur():
    // Langkah 1: Panaskan minyak dalam wajan
    panaskan_wajan()

    // Langkah 2: Pecahkan telur ke dalam wajan
    pecahkan_telur()

    // Langkah 3: Tunggu hingga telur setengah matang
    tunggu_hingga_setengah_matang()

    // Langkah 4: Balik telur
    balik_telur()

    // Langkah 5: Tunggu hingga matang sempurna
    tunggu_hingga_matang_sempurna()

    // Langkah 6: Angkat telur dari wajan
    angkat_telur()

procedure panaskan_wajan():
    // Aktifkan kompor dan panaskan wajan
    set suhu_kompor = tinggi
    set suhu_wajan = panas

procedure pecahkan_telur():
    // Pecahkan telur ke dalam wajan
    tambahkan telur ke dalam wajan

procedure tunggu_hingga_setengah_matang():
    // Tunggu hingga telur setengah matang
    while sisi_bawah_telur_belum_matang():
        tunggu()

procedure balik_telur():
    // Balik telur untuk memasak sisi atasnya
    balik telur
    // Tunggu sebentar setelah membalik telur
    tunggu()

procedure tunggu_hingga_matang_sempurna():
    // Tunggu hingga telur matang sempurna
    while sisi_atas_telur_belum_matang():
        tunggu()

procedure angkat_telur():
    // Angkat telur dari wajan
    angkat telur dari wajan
    // Matikan kompor
    matikan_kompor()

procedure sisi_bawah_telur_belum_matang():
    // Periksa apakah sisi bawah telur masih mentah
    return suhu_sisi_bawah_telur < suhu_matang

procedure sisi_atas_telur_belum_matang():
    // Periksa apakah sisi atas telur masih mentah
    return suhu_sisi_atas_telur < suhu_matang

procedure tunggu():
    // Tunggu sebentar sebelum memeriksa kembali suhu telur
    sleep(1)

procedure matikan_kompor():
    // Matikan kompor setelah telur matang
    set suhu_kompor = mati

```