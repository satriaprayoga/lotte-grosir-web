<template>
    <div id="footer">
        <div class="container">
        <div class="copybox">
            <div id="head_footer">
                LOTTEMART INDONESIA
            </div>
            <div id="head_footer">
                Copyright 2017. LotteMart Indonesia. All Rights Reserved
            </div>
            <div id="head_footer">
                <ul>
                        <li>
                            <span>
                      <font-awesome-icon :icon="['fab','facebook']"></font-awesome-icon>
                   </span>
                        </li>
                         <li>
                            <span>
                      <font-awesome-icon :icon="['fab','twitter']"></font-awesome-icon>
                   </span>
                        </li>
                         <li>
                            <span>
                      <font-awesome-icon :icon="['fab','youtube']"></font-awesome-icon>
                   </span>
                        </li>
                        <li>
                            <span>
                      <font-awesome-icon :icon="['fab','instagram']"></font-awesome-icon>
                   </span>
                        </li>
                    </ul>
            </div>
            <div id="footer_img">
                <img src="../assets/logo-tmuk.png" alt="">
            </div>
            
        </div>
    </div>
    </div>
</template>
<script>
export default {
    name:'app-footer'    
}
</script>
<style>

#footer .container{
    margin-top: -3px;
    padding-top: 68px;
    padding-bottom: 50px;
    margin-bottom: 30px;
    max-width: 100%;
    background-color: #2D87C5;;
}


#head_footer{
    text-align: center;
    color: #fff;
    margin-bottom: 20px;
    font-size: 14px;
}

#footer .row{
    border-width: 3px solid #ccc;
}

#footer ul{
    list-style: none;
    text-align: center;
    margin-right:30px;
}

#footer li{
   display: inline-block;
   margin-left: 1px;
}

#footer li span{
    text-align: center;
   line-height: 30px;
   font-size: 30px;
}



#footer #footer_img{
    
    margin-top: -80px;
}

</style>
