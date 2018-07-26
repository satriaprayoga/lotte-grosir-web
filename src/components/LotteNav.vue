<template>
    <header class="lottenav">
        <div class="nav-content">
             <div class="nav-left"> 
                <a class="nav-item bg-red" v-on:click="isChange=!isChange">
                    <span class="hamburger" v-bind:class="{change:isChange}">
                        <div class="bar1"></div>
                        <div class="bar2"></div>
                        <div class="bar3"></div>
                    </span>
                </a>
                <a href="#" class="nav-item logo">
                    <img src="../assets/lotte-grosir.png">
                </a>
             </div>
        </div>
     
    </header>
    
   
</template>

<script>
export default {
    name:'lotte-nav',
    data(){
        return{
            isChange:false,
        }
       
    },
    methods:{
        toggleBar(){
            this.isChange=!this.isChange
            console.log('toggle');
        }
    }
}
</script>

<style>
.lottenav{
    align-items: stretch;
    background-color: #fff;
    display: flex;
    min-height: 3.5rem;
    position: relative;
    text-align: center;
    z-index: 2;
}
.lottenav .nav-content{
    align-items: stretch;
    display: flex;
    min-height: 3.5rem;
    width: 100%;
}
.lottenav .nav-left{
    display: flex;
    justify-content: flex-start;
    overflow: hidden;
    overflow-x: auto;
    white-space: nowrap;
}
.lottenav .nav-left, 
.nav-right{
    align-items: stretch;
    flex-basis: 0;
    flex-grow: 1;
    flex-shrink: 0;
}

.lottenav .nav-right {
    justify-content: flex-end;
}

.lottenav .nav-item {
    font-size: 20px;
    align-items: center;
    display: flex;
    flex-grow: 0;
    flex-shrink: 0;
    font-size: 1rem;
    justify-content: center;
    padding-top: .75rem;
    padding-left: 1rem;

}
.lottenav .nav-item.bg-red {
    background-color: #2384c6;
    justify-content: center;
}

.lottenav .nav-item.bg-grey {
    background-color: #e3e3e3;
}

.lottenav .nav-item.logo {
   margin-left: 10px;
   margin-top: -15px;
}

.lottenav .nav-item a{
    color: #7a7a7a;
}

.lottenav .nav-item img {
   max-height: 1.75rem;
}

.lottenav .nav-item i{
    width: 50px;
}

.fa{
    font-size: 21px;
    text-align: center;
    vertical-align: top;
}
.lottenav .hamburger{
    position: relative;
    width: 50px;
    height: 50px;
    cursor: pointer;
    transition: all .4s ease;
    -webkit-transition: all .4s ease;
    -moz-transition: all .4s ease;
    -ms-transition: all .4s ease;
    -o-transition: all .4s ease;
}
.bar1, .bar2, .bar3 {
    width: 25px;
    height: 2px;
    background-color: #fff;
    margin: 6px 0;
    transition: 0.4s;
}

.change .bar1 {
    -webkit-transform: rotate(-45deg) translate(-9px, 9px);
    transform: rotate(-45deg) translate(-9px, 9px);
}

.change .bar2 {opacity: 0;}

.change .bar3 {
    -webkit-transform: rotate(45deg) translate(-2px, -2px);
    transform: rotate(45deg) translate(-2px, -2px);
}
</style>
