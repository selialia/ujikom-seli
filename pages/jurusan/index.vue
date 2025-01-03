<template>
  <div class="row">
    <div class="col">
      <div class="kompetensi-section">
        <div class="kompetensi-header">
          <i class="icon bi-mortarboard-fill"></i>
          <h1>Kompetensi Keahlian</h1>
        </div>
      </div>
    </div>
  </div>

  <div class="row">
    <div class="col">
      <div class="table-wrapper" style="display: flex; overflow-x: auto; padding: 20px;">
        <table class="table" style="min-width: 1200px; border-collapse: collapse; width: 100%;">
          <thead>
            <tr>
              <th>Gambar</th>
              <th>Kompetensi Keahlian</th>
              <th>Deskripsi</th>
              <th>Jurusan</th>
            </tr>
          </thead>
          <tbody>
            <!-- Baris 1 -->
            <tr>
              <td>
                <img src="~/assets/rpl.jpg" alt="Pengembangan Perangkat Lunak & Gim" style="width: 100px; height: 100px; object-fit: cover;"/>
              </td>
              <td>Pengembangan Perangkat Lunak & Gim</td>
              <td>Pemrograman dan Pengembangan software, Aplikasi web dan mobile, Game, UI/UX, Algoritma dan Logika Pemrograman.</td>
              <td>PPLG</td>
            </tr>

            <!-- Baris 2 -->
            <tr>
              <td>
                <img src="~/assets/tjkt.jpg" alt="Teknik Jaringan Komputer dan Telekomunikasi" style="width: 100px; height: 100px; object-fit: cover;"/>
              </td>
              <td>Teknik Jaringan Komputer & Telekomunikasi</td>
              <td>Instalasi dan Konfigurasi Jaringan, Administrasi Server, Keamanan Siber, Perakitan dan Pemeliharaan Komputer.</td>
              <td>TJKT</td>
            </tr>

            <!-- Baris 3 -->
            <tr>
              <td>
                <img src="~/assets/otomotif.jpg" alt="Teknik & Bisnis Sepeda Motor" style="width: 100px; height: 100px; object-fit: cover;"/>
              </td>
              <td>Teknik & Bisnis Sepeda Motor</td>
              <td>Servis Sepeda Motor, Perbaikan dan Pemeliharaan Mesin, Bisnis Otomotif, Pemasaran dan Manajemen Pelayanan Pelanggan.</td>
              <td>TBSM</td>
            </tr>

            <!-- Baris 4 -->
            <tr>
              <td>
                <img src="~/assets/desain.jpg" alt="Desain Komunikasi Visual" style="width: 100px; height: 100px; object-fit: cover;"/>
              </td>
              <td>Desain Komunikasi Visual</td>
              <td>Desain Grafis, Multimedia, Animasi, Fotografi, Branding, UI/UX Design.</td>
              <td>DKV</td>
            </tr>

            <!-- Baris 5 -->
            <tr>
              <td>
                <img src="~/assets/otomasi.jpg" alt="Teknik Otomotif Industri" style="width: 100px; height: 100px; object-fit: cover;"/>
              </td>
              <td>Teknik Otomotif Industri</td>
              <td>Sistem Otomasi, Elektronik Kendali, IoT dalam Industri, Pemrograman Otomasi.</td>
              <td>TOI</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
  </div>
</template>
