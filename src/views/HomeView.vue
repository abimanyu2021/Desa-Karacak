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
      <p class="text-lg font-semibold">Visi Desa Karacak</p>
      <p>
        “Menciptakan Tata Kelola Pemerintahan Yang Amanah, Jujur, Transparan dan Bertanggungjawab dalam Rangka Mewujudkan Masyarakat Desa Karacak Yang Maju, Adil, Aman, dan Mandiri”
      </p>
      <p class="text-lg font-semibold">Misi< Desa Karacak/p>
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
          4. Meningkatkan perekonomian masyarakat berbasis pertanian, peternakan, perikanan melalui kelompok dan UKM yang produktif  sesuai dengan potensi Desa dan peluang pasar;
        </li>
        <li>
          5. Menyelenggarakan pelatihan dan penyuluhan bagi kelompok pertanian, peternakan, perikanan, UKM dan bagi masyarakat pada umumnya sesuai dengan kebutuhan;
        </li>
        <li>
          6. Membentuk Badan Usaha Milik Desa (BUMDes) dan unit-unitnya sebagai lembaga yang mengelola produktivitas usaha masyarakat;
        </li>
        <li>
          7. Menjalin kerja sama dengan semua pihak dalam rangka peningkatan mutu kesejahteraan masyarakat;
        </li>
        <li>
          8. Membangun pola kehidupan masyarakat yang sehat melalui peningkatan kualitas kegiatan posyandu balita, posyandu lansia, kebersihan lingkungan secara umum dan pembangunan rumah tidak layak huni berdasarkan skala prioritas;
        </li>
        <li>
          9. Mengembalikan fungsi organisasi-organisasi masyarakat Desa Karacak untuk membantu pemerintah Desa dalam penyelenggaraan Pemerintahan atas dasar kepentingan masyarakat pada umumnya;
        </li>
        <li>
          10. Mengorganisir kaum muda Desa Karacak  dan meningkatkan perannya sebagai kader pembangunan dan kader pemimpin masa depan melalui Karang Taruna.
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
