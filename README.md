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
 
 Dan ini adalah hasil dari program tersebut


![1](https://user-images.githubusercontent.com/36159446/47692348-e34b5380-dc27-11e8-8b24-5f22bda3f85e.PNG)
![2](https://user-images.githubusercontent.com/36159446/47692349-e3e3ea00-dc27-11e8-8dac-55bb6449ffa3.PNG)
![3](https://user-images.githubusercontent.com/36159446/47692350-e3e3ea00-dc27-11e8-9b6c-b2b0632f8116.PNG)
