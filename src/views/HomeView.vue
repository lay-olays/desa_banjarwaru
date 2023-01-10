<script setup>
import Header from '../components/Header.vue'
import Banner from '../components/Banner.vue'
import Sidebar from '../components/Sidebar.vue'
</script>

<template>
  <Header/>
  <Banner/>
  <main class="flex">
    <Sidebar/>
    <div class="flex-1 p-10">


      <p class="text-3xl font-semibold">Visi & Misi Desa</p>
      <li>Mendorong peningkatan kesadaran dan penghayatan nilai-nilai ajaran agama yang menghargai keberagaman.</li>
                <li>Meningkatkan kualitas sumber daya masyarakat dan mengurangi pengangguran dan penduduk miskin.</li>
                <li>Meningkatkan kesejahteraan masyarakat dan mengurangi pengangguran dan penduduk miskin.</li>
                <li>Mendorong masyarakat mengembangkan usahanya melalui pembinaan yang terprogram dan bekerja sama dengan stakholder di sekitar desa.</li>

      <p class="text-3xl font-semibold my-4">Struktur Desa</p>
      <img src="@/assets/sotk-desa-banjarwaru.jpg" alt=""/>
    </div>
  </main>
</template>

<style>
  body{
    background: #f1f1f1;
  }
</style>
