<template>
    <main class="container mt-custom ">
        <div class="home bg-success text-white rounded text-center shadow mb-4">
            <h1>BISMILLAH</h1>
            <p class="lead content">
                Aplikasi ini diperuntukkan untuk kemudahan menghafal Al-Quran dengan metode JARIMATIKA. Aplikasi ini disusun dengan sumber ini dari
                <a href="https://quran.kemenag.go.id/" class="text-decoration-none text-warning"
                    target="_blank">Kementrian Agama Republik Indonesia
                </a> dengan murottal
                <strong>Misyari Rasyid Al-'Afasi</strong>, serta Sumber database API dari <a href="https://equran.id/" class="text-decoration-none text-warning"
                    target="_blank">Platform E-Quran.ID </a> untuk menjamin originalitas dan akurasi dari konten.
            </p>
            <!-- <div>
                <router-link :to="{ name: 'home' }" class="btn btn-warning m-1">Surah</router-link>
                <router-link :to="{ name: 'juz' }" class="btn btn-warning m-1">Juz</router-link>
            </div> -->
        </div>
    </main>
</template>

<script>
export default {
    name: 'HomeVue',
    components: {},
}
</script>

<style scoped>
.mt-custom {
    margin-top: 95px;
}

.home {
    padding: 30px;
}

@media screen and (max-width: 768px) {
    .home {
        padding: 15px;
    }

    .content {
        font-size: 15px;
    }
}
</style>
