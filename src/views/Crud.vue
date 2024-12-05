<template>
    <div class="container mt-5">
        <div class="d-flex justify-content-between align-items-center">
            <!-- Form Title -->
            <h2>Formulir Pendaftaran</h2>

            <!-- Back Button -->
            <RouterLink to="/" class="btn btn-primary" aria-label="Kembali ke Home">
                Kembali
            </RouterLink>
            
        </div>
    </div>
    <div class="registration-form container mt-5">
        <!-- Username -->
        <div class="mb-3">
            <label for="username" class="form-label">Username</label>
            <div class="input-group">
                <input type="text" id="username" class="form-control" placeholder="Enter your username"
                    aria-label="Username" aria-describedby="username-addon">
            </div>
        </div>

        <!-- Email -->
        <div class="mb-3">
            <label for="email" class="form-label">Email Address</label>
            <div class="input-group">
                <input type="text" id="email" class="form-control" placeholder="Enter your email" aria-label="Email"
                    aria-describedby="email-addon">
                <span class="input-group-text" id="email-addon">@example.com</span>
            </div>
        </div>

        <!-- Nomor WA -->
        <div class="mb-3">
            <label for="whatsapp" class="form-label">Nomor WhatsApp</label>
            <div class="input-group">
                <span class="input-group-text" id="whatsapp-addon">+62</span>
                <input type="tel" id="whatsapp" class="form-control" placeholder="Masukkan nomor WhatsApp Anda"
                    aria-label="Nomor WhatsApp" aria-describedby="whatsapp-addon">
            </div>
        </div>


        <!-- Submit Button -->
        <button type="submit" class="btn btn-primary w-100">Register</button>
    </div>


</template>

<script>
import { RouterLink } from 'vue-router';

export default {
    name: "Crud"
}
</script>

<style></style>