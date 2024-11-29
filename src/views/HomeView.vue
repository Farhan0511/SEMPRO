<template>
  <div>
    <navbar />

    <div class="container my-5">
      <div class="card shadow-lg rounded overflow-hidden">
        <div class="row g-0">

          <!-- Bagian Gambar -->
          <div class="col-md-6">
            <img src="/disabilitas.jpg" alt="Ilustrasi Program Rehabilitasi Sosial"
              class="img-fluid h-100 w-100 object-fit-cover">
          </div>

          <!-- Bagian Teks -->
          <div class="col-md-6 d-flex align-items-center">
            <div class="card-body p-4 bg-light">
              <h2 class="card-title text-primary mb-4 fw-semibold">Program Rehabilitasi Sosial</h2>
              <p class="card-text text-muted fs-5">
                Bantuan digital ini bertujuan untuk mendukung individu dan kelompok yang membutuhkan akses teknologi,
                membantu mereka meningkatkan kemandirian ekonomi dan kualitas hidup di era digital.
              </p>
              <p class="card-text text-muted fs-5">
                Dengan dukungan pembuatan website, penerima manfaat dapat memperluas peluang, memaksimalkan potensi,
                serta membangun kembali kehidupan yang lebih stabil dan produktif.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Progrma -->
    <div class="container my-5">
      <div class="text-center mb-5">
        <h2>Program yang sudah dijalankan</h2>
      </div>

      <div class="row g-4">
        <div class="col-md-4">
          <div class="card" style="width: 100%;">
            <img src="..." class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's
                content.</p>
              <a href="#" class="btn btn-primary">Go somewhere</a>
            </div>
          </div>
        </div>

        <div class="col-md-4">
          <div class="card" style="width: 100%;">
            <img src="..." class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's
                content.</p>
              <a href="#" class="btn btn-primary">Go somewhere</a>
            </div>
          </div>
        </div>

        <div class="col-md-4">
          <div class="card" style="width: 100%;">
            <img src="..." class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's
                content.</p>
              <a href="#" class="btn btn-primary">Go somewhere</a>
            </div>
          </div>
        </div>
      </div>
    </div>


    <!-- Footer -->
    <div>
      <Footer />

    </div>

  </div>
</template>

<script>
import Navbar from '@/components/Navbar.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: "HomeView",
  components: {
    Navbar,
    Footer,
  }

}
</script>

<style></style>