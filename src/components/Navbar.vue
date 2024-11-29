<template>
    <div>
        <nav class="p-4 navbar navbar-expand-lg navbar-light bg-light">
            <div class="container">
                <!-- Brand -->
                <RouterLink class="navbar-brand fs-4 fw-bold " to="/">MyApp</RouterLink>

                <!-- Toggler for Mobile -->
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                    aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>

                <!-- Navbar Links -->
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav ms-auto ">
                        <!-- Home -->
                        <li class="nav-item">
                            <RouterLink class="nav-link fs-5 text-black" to="/">Home</RouterLink>
                        </li>

                        <!-- About -->
                        <li class="nav-item">
                            <RouterLink class="nav-link fs-5 text-black" to="/about">About</RouterLink>
                        </li>

                        <!-- Student -->
                        <li class="nav-item">
                            <RouterLink class="nav-link fs-5 text-black" to="/student">Student</RouterLink>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    </div>
</template>

<script>
export default {
    name: "Navbar",
};
</script>

<style scoped>
/* Optional: Styling for active links */
.nav-link.active {
    font-weight: bold;
    color: #0d6efd !important;
    border-bottom: 2px solid #0d6efd;
}

/* Optional: Hover effect */
.nav-link:hover {
    color: #0d6efd !important;
}
</style>