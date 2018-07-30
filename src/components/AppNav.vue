<template>
    <b-navbar id="appNav" toggleable="md">
        <b-navbar-toggle target="nav_collapse"></b-navbar-toggle>
        <b-navbar-brand>TMUK</b-navbar-brand>
        <b-collapse is-nav id="nav_collapse">
            <b-navbar-nav class="ml-auto">
            <b-nav-item href="#">Keunggulan</b-nav-item>
            <b-nav-item href="#">Fitur</b-nav-item>
            <b-nav-item href="#">Testimoni</b-nav-item>
            <b-nav-item href="#">Lokasi</b-nav-item>
            <b-nav-item href="#">Daftar</b-nav-item>
        </b-navbar-nav>
        </b-collapse>
    </b-navbar>
</template>

<script>
export default {
  name: "app-nav"
};
</script>

<style>
#appNav {
  background-color: #1158A8;
}

#appNav .nav-link{
    color:#FEF200;
}

</style>
