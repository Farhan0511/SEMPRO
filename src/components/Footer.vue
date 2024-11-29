<template>
    <div class="content">
        <!-- Konten lainnya -->
        <footer class="bg-dark text-light py-4 mt-auto">
            <div class="container text-center">
                <p class="mb-1">&copy; 2024 MyWebsite. All Rights Reserved.</p>
                <div>
                    <a href="https://facebook.com" target="_blank" class="text-light mx-2">
                        <i class="fab fa-facebook-f"></i>
                    </a>
                    <a href="https://twitter.com" target="_blank" class="text-light mx-2">
                        <i class="fab fa-twitter"></i>
                    </a>
                    <a href="https://instagram.com" target="_blank" class="text-light mx-2">
                        <i class="fab fa-instagram"></i>
                    </a>
                </div>
            </div>
        </footer>
    </div>
</template>

<script>
export default {
    name: 'Footer'
}
</script>

<style scoped>
/* Container utama di layout flex */
.content {
    display: flex;
    flex-direction: column;
    min-height: 100vh;
}

/* Pastikan footer tetap di bawah dengan margin-top auto */
footer {
    margin-top: auto;
    background-color: #333;
    color: white;
    padding: 20px 0;
    text-align: center;
}

footer a {
    color: white;
    margin: 0 10px;
}

footer a:hover {
    color: #ddd;
}
</style>