<template>
  <div>
    <navbar />

    <div class="container my-5">
      <div class="row align-items-center">
        <!-- Bagian Teks -->
        <div class="col-md-6">
          <h2 class="mb-4">Program Rehabilitasi Sosial</h2>
          <p>
            Bantuan digital ini bertujuan untuk mendukung individu dan kelompok yang membutuhkan akses teknologi,
            membantu mereka meningkatkan kemandirian ekonomi dan kualitas hidup di era digital.
          </p>
          <p>
            Dengan dukungan pembuatan website, penerima manfaat dapat memperluas peluang, memaksimalkan potensi,
            serta membangun kembali kehidupan yang lebih stabil dan produktif.
          </p>
        </div>

        <!-- Bagian Gambar -->
        <div class="col-md-6 text-center">
          <img src="/public/disabilitas.jpg" alt="Ilustrasi Program Rehabilitasi Sosial" class="img-fluid rounded">
        </div>
      </div>
    </div>

  </div>
</template>

<script>
import Navbar from '@/components/Navbar.vue';

export default {
  name: "HomeView",
  components: {
    Navbar,
  }

}
</script>

<style></style>