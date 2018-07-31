<template>
    <div class="about">
       <div class="jumbotron">
           <div class="row">
               <div class="col-md-8 col-xs-6 naration">
                    <h1 class="display-3">
                        {{head}}
                    </h1>
                    <p>{{lead}}</p>
                    <br>
                    <p>{{lead_newline}}</p>
                    <h2>{{lead_list.list_head}}</h2>
                    <ol>
                        <li v-for="item in lead_list.list_childs">
                            {{item}}
                        </li>
                    </ol>
                    <a href="#" class="btn btn-default">Daftar Sekarang! (GRATIS)</a>
               </div>
               <div class="col-md-4 col-xs-6">
                   <div>
                       <img src="../assets/tmuk-mart-opt.png">
                   </div>
               </div>
           </div>
       </div>
    </div>
</template>

<script>

export default {
    name:'about',
    data(){
        return{
            head:"TOKO MITRA USAHA KITA-KITA",
            lead:"TMUK atau yang lebih dikenal sebagai Toko Mitra Usaha Kita-Kita "+
            "merupakan sebuah kerjasama kemitraan berbentuk program modernisasi warung/toko tradisional agar bisa menjadi "+
            "sebuah toko modern dengan meliput modernisasi interior atau penataan layout dagangan dan juga eksterior toko sehingga memiliki penampilan standar minimarket",
            lead_newline:"Program TMUK ini adalah suatu bentuk pembinaan terhadap warung/toko tradisional "+
            "meliputi pembinaan operasional, sumberdaya manusia & administrasi toko oleh Team TMUK dari LOTTE Grosir kepada pemilik warung/ mitra "+
            ",dimana mitra fokus pada manajemen toko & aktivitas penjualan sementara Lotte Grosir akan mendukung pada aktivitas penunjang penjualan "+
            "sehingga mitra memperoleh kemudahan untuk tetap mengelola tokonya secara mandiri",
            lead_list:{
                list_head:"Dukungan Lotte Grosir dimulai dari tahap:",
                list_childs:[
                    "Pra pembukaan meliputi survey lokasi, kelayakan bisnis, desain layout, planogram, rekomendasi barang",
                    "Pembukaan TMUK meliputi supervisi setting toko, bantuan display barang, usulan program promosi",
                    "Pelatihan & Pengawasan TMUK meliputi pelatihan pengawasan, pelaksanaan SOP operasional, laporan administrasi"
                ]
            }
  
        }     
    }
}
</script>

<style>
.about{
    width: 100%;
    top: 0;
    left: 0;
    z-index: -1;
}

.about .jumbotron{
     background: linear-gradient(to bottom right,#1061B0,#2D87C5);
      margin: auto;
      border-radius: 0px;
      padding-bottom: 0;
      padding-top: 0;
}

.about .jumbotron .naration{
    margin-top: 10px;
}

.about .jumbotron img{
   
      margin-left: 39px;
}


.about .display-3{
    font-size: 36px;
    font-weight: 500;
    color: #FEF200;
}

.about h2{
    font-size: 36px;
    color: #fff;
}

.about .jumbotron p, li{
    font-size: 14px;
    color:#fff;
}

.about .jumbotron .btn{
  border-radius: 1px !important;
  border-color:green;
  border-width: 3px;
  background-color:yellow;
  color: rgb(3, 0, 0);
  font-size: 20px;
  font-weight: bold;
}

.about .jumbotron .btn:hover{
  background-color: #fff;
  color: rgb(3, 0, 0);
}

</style>
