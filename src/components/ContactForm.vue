<template>
<div id="form">
        <div class="container-fluid contact-form">
            <h1 class="head-form">Punya Lahan Dan Tertarik Buka Usaha TMUK?</h1>
            <div class="col-xs-12 col-sm-12 col-md-12 col-lg-12" style="text-align: center;">
                <div class="col-md-6 offset-md-3 registeration">
                    <div class="registerInner">
                        <div class="col-md-12">
                            <h3 class="headerSign" style="padding-bottom: 60px;"></h3>
                            <div id="embed_signup">
                                <form id="embed_subscribe_form">
                                    <div class="indicates-required">
                                        <span class="asterix">*</span>
                                        wajib diisi
                                    </div>
                                    <div class="form-group">
                                        <label for="name">
                                            Nama Anda
                                            <i>(Sesuai KTP)</i>
                                            <span class="asterix">*</span>
                                        </label>
                                        <input type="text" name="name" class="form-control" >
                                    </div>
                                     <div class="form-group">
                                        <label for="email">
                                            Email Anda
                                             <span class="asterix">*</span>
                                        </label>
                                        <input type="email" name="email" class="form-control" >
                                    </div>
                                    <div class="form-group">
                                        <label for="phone">
                                            No. Telepon
                                            <i>(Aktif WhatsApp)</i>
                                            <span class="asterix">*</span>
                                        </label>
                                        <input type="tel" name="phone" class="form-control" >
                                    </div>
                                </form>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <img src="../assets/footer.png" alt="" class="img-fluid">
        </div>
    </div>
</template>

<script>
export default {
    name:'contact-form'
}
</script>

<style>
.contact-form{
  margin-top: 0;
  padding-top: 68px;
  padding-bottom: 0px;
  background-color: #E4E6E5; 
}

.contact-form .head-form{
  margin-bottom: 30px;
  text-align: center;
  color: #2D87C5;
  
}

.contact-form .registeration
{
  border-top: 5px solid #2D87C5;
  -webkit-box-shadow: 0px 5px 21px -2px rgba(0, 0, 0, 0.47);
    -moz-box-shadow: 0px 5px 21px -2px rgba(0, 0, 0, 0.47);
    box-shadow: 0px 5px 21px -2px rgba(0, 0, 0, 0.47);
    margin-bottom: 30px;
    background-color: #fff;
    font-weight: bold;
}

.contact-form .registerInner{
  margin: 10px;
}

.contact-form .headerSign{
  color: #2384c6;
  margin-bottom: 20px;
  text-align: center;
}

.contact-form #embed_signup form{
  display: block;
  position: relative;
  text-align: left;
  padding: 10px 0 10px 3%
}

.contact-form #embed_signup .indicates-required{
  text-align: right;
    font-size: 11px;
    margin-right: 4%;
    margin-top: -5%;
    
}
.contact-form #embed_signup .asterix{
    color: #e85c41;
    font-size: 150%;
    font-weight: normal;
    position: relative;
    top: 5px;
}

.contact-form input{
    border-top: none !important;
  border-right: none !important;
  border-left: none !important;
  border-bottom: 1px dotted #2D87C5!important;
  box-shadow: none !important;
  -webkit-box-shadow: none !important;
  -moz-box-shadow: none !important;
  -moz-transition: none !important;
  -webkit-transition: none !important;
}

.contact-form img{
    margin-left: 150px;
}
</style>
