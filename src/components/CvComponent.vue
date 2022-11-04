<template>
  <div class="container mt-4 mb-4">
    <h1 style="text-align: center"><b>CV LAMARAN KERJA</b></h1>
    <div class="bungkus mt-4">
      <div class="biodata p-5">
        <img
          src="../assets/photo_6278429021050090383_y.jpg"
          class="card-img-top"
          alt=""
          style="border-radius: 50%; width: 250px"
        />
        <br />
        <br />
        <hr />
        <h5 class="nama">Nama:</h5>
        <p>Aveceena intifadha firdaus ming</p>
        <h5 class="alamat">Alamat:</h5>
        <p>Ambarawa</p>
        <h5 class="Ttl">Ttl:</h5>
        <p>Ambarawa, 17 Mei, 2007</p>
        <h5 class="umur">Umur:</h5>
        <p>15</p>
        <h5 class="Sekolah">Sekolah:</h5>
        <p>Bina Nusantara Demak</p>
        <h5 class="whatsapp">WhatsApp:</h5>
        <p>089608466996</p>
        <h5 class="fb">Facebook:</h5>
        <p>Ave Ceena</p>
        <h5 class="instagram">Instagram:</h5>
        <p>aveceena07</p>
        <h5 class="tiktok">Tik Tok:</h5>
        <p>aveceena17</p>
        <h5 class="hobi">Hobi</h5>
        <p>- Bermain Bulu Tangkis</p>
        <p>- Berenang</p>
        <hr />
        <div class="medsos">
          <a href="https://instagram.com/aveceena07?igshid=YmMyMTA2M2Y="
            ><i class="fa-brands fa-instagram fs-4"></i
          ></a>
          &nbsp;
          <a href="https://www.facebook.com/"
            ><i class="fa-brands fa-facebook fs-4"></i
          ></a>
          &nbsp;
          <a
            href="https://www.tiktok.com/@aveceena17?_r=1&_d=e2bk9l0ihc6lma&language=id&sec_uid=MS4wLjABAAAAPmQDwm-0Q0v5-NQr4Aj4ZDZ9TcUXitGyzYQaNUYDak7tC2xtnBYXkGnhxpfDRxIO&share_author_id=7018072759403168794&source=h5_t&u_code=dl5f43g4d82738&timestamp=1667448190&user_id=7018072759403168794&sec_user_id=MS4wLjABAAAAPmQDwm-0Q0v5-NQr4Aj4ZDZ9TcUXitGyzYQaNUYDak7tC2xtnBYXkGnhxpfDRxIO&utm_source=copy&utm_campaign=client_share&utm_medium=android&share_iid=7161582013546432282&share_link_id=b387f7fa-c5f0-405e-8368-b850a873be00&share_app_id=1180&ugbiz_name=Account&ug_btm=b8727%2Cb4907
"
            ><i class="fa-brands fa-tiktok fs-4"></i
          ></a>
          &nbsp;
          <a href="https://twitter.com/"
            ><i class="fa-brands fa-square-twitter fs-4"></i
          ></a>
        </div>
      </div>

      <div class="px-5">
        <h3 class="tentang">
          <i class="fa-solid fa-user fs-2"></i> Tentang Saya
        </h3>
        <p class="desc">
          Nama lengkap saya adalah Aveceena intifadha firdaus ming,dan nama
          panggilan saya adalah Ave,Saya lahir di RSUD Dr. Gunawan Mangunkusumo
          Kecamatan Ambarawa pada tanggal 17 Bulan Mei tahun 2007.
        </p>
        <hr />
        <h3 class="riwayat">
          <i class="fa-solid fa-graduation-cap fs-2"></i> Riwayat Pendidikan
        </h3>
        <p>PAUD: Baitusalam Ambarawa</p>
        <p>TK: Assalam Bandungan</p>
        <p>SD: SDIP H.M Soebandi</p>
        <p>MTS: Mts H.M Subandi</p>
        <p>SMK: Smk Bina Nusantara</p>
        <hr />
        <h3 class="pengalaman">
          <i class="fa-sharp fa-solid fa-suitcase fs-2"></i> Pengalaman Kerja
        </h3>
        <p>Kerja Kelompok</p>
        <p>Kerja Bakti</p>
        <hr />
        <h3 class="ahli"><i class="fa-solid fa-gears fs-2"></i> Keahlian</h3>

        <div class="progress">
          <div
            class="progress-bar"
            role="progressbar"
            aria-label="Example with label"
            style="width: 79%"
            aria-valuenow="25"
            aria-valuemin="0"
            aria-valuemax="100"
          >
            HTML
          </div>
        </div>

        <div class="progress mt-2">
          <div
            class="progress-bar"
            role="progressbar"
            aria-label="Example with label"
            style="width: 75%"
            aria-valuenow="25"
            aria-valuemin="0"
            aria-valuemax="100"
          >
            CSS
          </div>
        </div>

        <div class="progress mt-2">
          <div
            class="progress-bar"
            role="progressbar"
            aria-label="Example with label"
            style="width: 55%"
            aria-valuenow="25"
            aria-valuemin="0"
            aria-valuemax="100"
          >
            JavaScript
          </div>
        </div>
        <br />
        <hr />
        <h3 class="karakter"><i class="fa-solid fa-user fs-2"></i> Karakter</h3>
        <br />
        <p>- Baik</p>
        <p>- Sopan</p>
        <p>- Jujur</p>
        <p>- Suka hal baru</p>
        <p>- Bertanggung jawab</p>
        <br />
        <hr />
        <h3 class="organisasi">
          <i class="fa-solid fa-sitemap fs-2"></i> Pengalaman Organisasi
        </h3>
        <p>- OSIS</p>
        <p>- PRAMUKA</p>
        <p>- PMR</p>
        <p>- PASKIBRA</p>
        <p>- ROHIS</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "CvComponent",
};
</script>

<style>
.container {
  background-color: aliceblue;
}
.nama {
  text-decoration: underline;
}
.alamat {
  text-decoration: underline;
}
.Ttl {
  text-decoration: underline;
}
.umur {
  text-decoration: underline;
}
.Sekolah {
  text-decoration: underline;
}
.whatsapp {
  text-decoration: underline;
}
.fb {
  text-decoration: underline;
}
.instagram {
  text-decoration: underline;
}
.tiktok {
  text-decoration: underline;
}
.hobi {
  text-decoration: underline;
}
.bungkus {
  display: flex;
  font-family: Arial, Helvetica, sans-serif;
  padding: 10px;
  background-color: whitesmoke;
}
.tentang {
  background-color: whitesmoke;
  font-family: sans-serif;
}
.karakter {
  background-color: whitesmoke;
  font-family: sans-serif;
}
.riwayat {
  background-color: whitesmoke;
  font-family: sans-serif;
}
.organisasi {
  background-color: whitesmoke;
  font-family: sans-serif;
}
.pengalaman {
  background-color: whitesmoke;
  font-family: sans-serif;
}
.ahli {
  background-color: whitesmoke;
  font-family: sans-serif;
}
.biodata {
  background-color: gainsboro;
  float: right;
  font-family: sans-serif;
  font-size: large;
}

.desc {
  text-align: justify;
}
</style>
