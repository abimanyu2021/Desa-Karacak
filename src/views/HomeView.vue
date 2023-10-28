<script setup>
import Header from "../components/Header.vue";
import Banner from "../components/Banner.vue";
import Sidebar from "../components/Sidebar.vue";
</script>

<template>
  <Header />
  <Banner />

  <main class="flex">
    <Sidebar />

    <div class="flex-1 p-10">
      <p class="text-3xl font-semibold">Visi & Misi Desa Karacak</p>
      <p class="text-lg font-semibold">Visi</p>
      <p>
        “Menciptakan Tata Kelola Pemerintahan Yang Amanah, Jujur, Transparan dan Bertanggungjawab dalam Rangka Mewujudkan Masyarakat Desa Karacak Yang Maju, Adil, Aman, dan Mandiri”
      </p>
      <p class="text-lg font-semibold">Misi</p>
      <ul>
        <li>
          1. Melakukan perbaikan sistem kinerja aparatur pemerintahan desa guna meningkatkan kualitas pelayanan kepada masyarakat;
        </li>
        <li>
          2. Menyelenggarakan pemerintahan yang baik, bebas dari bentuk-bentuk penyelewengan;
        </li>
        <li>
          3. Menyelenggarakan urusan pemerintahan desa secara terbuka dan bertanggungjawab sesuai dengan peraturan perundang-undangan;
        </li>
        <li>
          4. 4.	Meningkatkan perekonomian masyarakat berbasis pertanian, peternakan, perikanan melalui kelompok dan UKM yang produktif  sesuai dengan potensi Desa dan peluang pasar;
        </li>
        <li>
          5. Meningkatkan kemampuan dan pemberdayaan Lembaga-lembaga
          kemasyarakatan yang ada didesa atau lebih mendinamisasi dan mendukung
          seluruh proses pembangunan;
        </li>
        <li>
          6. Mendorong majunya Pendidikan formal maupun nonformal seperti
          pesantren, LPK, diklat serta penyuluhan pertanian yang mudah diakses
          dan dinikmati seluruh warga masyarakat, guna menghasilkan insan
          intelektual, berakhlak mulia, inovatif dan entrepreneur;
        </li>
        <li>
          7. Menyalurkan segala bentuk bantuan dari Pemerintah Kabupaten,
          Provinsi dan Pusat sesuai dengan peruntukannya dan mencegah terjadinya
          penyimpangan dan kebocoran;
        </li>
        <li>
          8. Menjalin sinergitas dengan instansi atau Lembaga terkait dan pihak
          swasta guna optimalisasi suatu tujuan lebih baik dan lebih maksimal;
        </li>
        <li>
          9. Responsive dan aspiratif atas segala bentuk kebutuhan atau
          keinginan dan permasalahan yang terjadi ditengah masyarakat yang
          majemuk dan dinamis;
        </li>
        <li>
          10. Membina dan memantapkankehidupan gotong royongsebagai basis dan
          modal dasar pembangunan desa, yang pada hakikatnyajuga merupakan
          karakter dasar dari masyarakat desa dan juga bangsa Indonesia.
        </li>
      </ul>
    </div>
  </main>
</template>

<style>
body {
  background: #f1f1f1;
}
</style>
