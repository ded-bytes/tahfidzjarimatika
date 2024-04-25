<template>
    <footer class="footer bg-dark text-white p-3">
        <div class="container">
            <div class="row pt-5">
                <div class="col-md-2 text-center">
                    <img src="../../public/img/icons/favicon-32x32.png" class="justify-content-center logo" alt="">
                </div>
                <div class="col-md-6">
                    <h5>Tahfidz Jarimatika</h5>
                    <p class="text-muted">
                        Sebuah Aplikasi Oleh Rizky Mutmainnah yang digunakan untuk pemudahan Tahfidz dengan metode jarimatika.
                    </p>
                </div>
                <div class="col-md-2">
                    <h5>Social Media</h5>
                    <ul class="list-unstyled">
                        <li><a href="https://www.instagram.com/rizki_mthmainnahamr/" class="text-decoration-none text-white"
                                target="_blank">Researcher</a>
                        </li>
                        <li><a href="https://www.instagram.com/pammipams_/"
                                class="text-decoration-none text-white" target="_blank">Developer</a>
                        </li>
                    </ul>
                </div>
                <div class="col-md-2">
                    <h5>Sources</h5>
                    <ul class="list-unstyled">
                        <li><a href="https://quran.kemenag.go.id/"
                                class="text-decoration-none text-white" target="_blank">Kementrian Agama</a></li>
                        <li><a href="https://equran.id/"
                                class="text-decoration-none text-white" target="_blank">E-Quran.ID</a></li>        
                    </ul>
                </div>
            </div>
            <hr>
            <div class="row">
                <div class="col-md-12 justify-content-center text-center">
                    <span class="">
                        Made for Rizky Mutmainnah . All Rights & Exclusivity Included 
                    </span>
                </div>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    name: 'FooterVue',
    components: {},
}
</script>

<style scoped>
.mt-9 {
    margin-top: 9rem;
}

img.logo {
    width: 75%;
}

@media only screen and (max-width: 768px) {
    img.logo {
        width: 50%;
    }

    .footer {
        text-align: center;
    }
}
</style>