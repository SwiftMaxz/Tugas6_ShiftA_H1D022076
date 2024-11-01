# Menambahkan Komponen di Halaman Ionic
Berikut adalah langkah-langkah untuk menambahkan komponen baru di halaman Ionic:

## 1. Mencari komponen yang dibutuhkan
Mencari komponen yang dibutuhkan seperti card, button, dan svg avatar pada [website dokumentasi komponen ionic](https://ionicframework.com/docs/components) 

## 2. Menerapkan Komponen pada Halaman
Setelah mendapat komponen, selanjutnya tingal menambahkan komponen tersebut ke halaman `folder.page.html`.
Berikut bagian komponen yang ditambahkan dan telah dimodifikasi:
```
<div id="info-card">
      <ion-card>
        <img src="https://ionicframework.com/docs/demos/api/avatar/avatar.svg" alt="Avatar" class="profile-pic" />
        <ion-card-header>
          <ion-card-title>Gery Prayoga</ion-card-title>
          <ion-card-subtitle>H1D022076</ion-card-subtitle>
        </ion-card-header>
        <ion-card-content>
          <p>Check out my Instagram!</p>
          <ion-button size="small" expand="block" color="secondary" href="https://instagram.com/masger28_" target="_blank">
            <ion-icon name="logo-instagram" slot="start"></ion-icon>
            Visit Instagram
          </ion-button>
        </ion-card-content>
      </ion-card>
    </div>
```
```
<div id="extras">
      <ion-card>
        <ion-card-header>
          <ion-card-title>About Me</ion-card-title>
        </ion-card-header>
        <ion-card-content>
          I believe in kindness, good coffee, and just going with the flow. Happy to be here and see where life takes me.
        </ion-card-content>
      </ion-card>
    </div>
```


## 3. Kustomisasi Tampilan
Kemudian mengkustomisasi tampilan agar sedikit lebih baik pada halaman `folder.page.scss`

# Screenshots

| ![SS1](firstApp/SS1.png) | ![SS2](firstApp/SS2.png) |
|-----------------------------------|------------------------------------------|
