<template>
    <div class="container-fluid ">
        <img src="../assets/pp.png" style="width: 100%;" alt="">
        <div class=" sambutan card p-4">
            <div class="row">
                <div class="col-3 pt-3">
                    <img src="../assets/kepala.png" style="width: 100%; " class="bg-primary rounded-5" alt="">
                </div>
                <div class="col-8 pt-3">
                    <h4>kurniawan, s.pd,m.pd</h4>
                    <h4>Assalamualaikum wr.wb</h4>
                    <h6>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nostrum aut eveniet distinctio deserunt laborum dolores, quod autem doloribus ipsum voluptatem quam a asperiores libero voluptas repellendus quia! Perferendis, autem necessitatibus.</h6>
                </div>
            </div>
        </div>
        <div class="berita my-5 pt-5 ">
            <h3 class="m-5">BERITA ARTIKEL & INFORMASI</h3>
            <div class="scroll-container py-5">
                <div class="card  mx-5" style="width: 20rem;">
                    <img src="../assets/berita.jpg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">JUDUL 1</h5>
                        <p class="card-text">isi kontennya</p>
                    </div>
                </div>
                <div class="card  mx-5" style="width: 20rem;">
                    <img src="../assets/berita.jpg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">JUDUL 1</h5>
                        <p class="card-text">isi kontennya</p>
                    </div>
                </div>
                <div class="card  mx-5" style="width: 20rem;">
                    <img src="../assets/berita.jpg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">JUDUL 1</h5>
                        <p class="card-text">isi kontennya</p>
                    </div>
                </div>
                <div class="card  mx-5" style="width: 20rem;">
                    <img src="../assets/berita.jpg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">JUDUL 1</h5>
                        <p class="card-text">isi kontennya</p>
                    </div>
                </div>
                <div class="card  mx-5" style="width: 20rem;">
                    <img src="../assets/berita.jpg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">JUDUL 1</h5>
                        <p class="card-text">isi kontennya</p>
                    </div>
                </div>
                <div class="card  mx-5 " style="width: 20rem;">
                    <img src="../assets/berita.jpg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">JUDUL 1</h5>
                        <p class="card-text">isi kontennya</p>
                    </div>
                </div>

            </div>
        </div>
        <div class="jurusan mt-5 pt-5">
            <h3 class="m-5">KOMPETENSI KEAHLIAN</h3>
            <div class="scroll-container">
                <div class="card  mx-5" style="width: 20rem;">
                    <img src="../assets/tkj.jpeg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">TEKNIK JARINGAN KOMPUTER DAN TELEKOMUNIKASI</h5>
                    </div>
                </div>
                <div class="card  mx-5" style="width: 20rem;">
                    <img src="../assets/rpl.jpeg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title"> PENGEMBANGAN PERANGKAT LUNAK DAN GIM</h5>
                    </div>
                </div>
                <div class="card  mx-5" style="width: 20rem;">
                    <img src="../assets/tsm.jpeg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">TEKNIK SEPEDAH MOTOR</h5>
                    </div>
                </div>
                <div class="card  mx-5" style="width: 20rem;">
                    <img src="../assets/dkv.jpeg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">DESAIN KOMUNIKASI VISUAL</h5>
                    </div>
                </div>
                <div class="card  mx-5" style="width: 20rem;">
                    <img src="../assets/toi.jpeg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">TEKNIK OTOMASI INDUSTRI</h5>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<style>
.scroll-container {
    display: flex;
    overflow-x: auto;
    gap: 1rem;
    padding: 1rem 0;
    scrollbar-width: thin;
}

.scroll-container::-webkit-scrollbar {
    height: 8px;
}

.scroll-container::-webkit-scrollbar-thumb {
    background-color: #aaa;
    border-radius: 4px;
}

.scroll-container::-webkit-scrollbar-track {
    background-color: #f1f1f1;
}

.card {
    flex: 0 0 auto;
}

.sambutan {
    width: 50%;
    position: absolute;
    top: 68%;
    right: 25%;
}
.berita{
    background-color: #4870A4;
}
</style>