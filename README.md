# SG_Tab_LayOut
Tugas Tab LayOut Android

Program ini bertujuan untuk membuat tab lay out pada android, khususnya ke arah samping.
 1. Buat lah beberapa file baru pada direktori res/layout untuk halaman - halaman lay out yang diinginkan ( pindah halaman kalau di swipe)
 2. Pada file tersebut atur width dan height menjadi wrap_content agar tinggi dan lebar menyesuaikan dengan object yang ada di dalamnya, 
    untuk mengisi/menulis pada tab tersebut ketik android:text="SG TELC 1" (misal)
 3. Pada file MainActivity buat object TabLayout dan ViewPager, lalu menginisiasi kedua hal tersebut
 4. Untuk menambahkan tab gunakan method addTab 
        tabLayout.addTab(tabLayout.newTab().setText("SG TELC 1"));
        tabLayout.addTab(tabLayout.newTab().setText("SG TELC 2"));
        tabLayout.addTab(tabLayout.newTab().setText("SG TELC 3"));
        tabLayout.setTabGravity(TabLayout.GRAVITY_FILL);
 5. Terakhir jangan lupa tambahkan
        tabLayout.setOnTabSelectedListener(this);
    untuk memberi tahu jika pengguna me-swipe maka akan pindah tab
    
