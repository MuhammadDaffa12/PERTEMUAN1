<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <div class="biodata-container">
    <h2>Biodata Mahasiswa</h2>
    <div class="biodata-item"><span class="label">Nama:</span> Muhammad Daffa</div>
    <div class="biodata-item"><span class="label">NIM:</span> 233510775</div>
    <div class="biodata-item"><span class="label">Program Studi:</span> Teknik Informatika</div>
    <div class="biodata-item"><span class="label">Semester:</span> 4</div>
    <div class="biodata-item"><span class="label">Kelas:</span> 4D</div>
    <div class="biodata-item"><span class="label">Deskripsi:</span> 
      Mahasiswa aktif yang tertarik pada pengembangan aplikasi web dan mobile, serta terus mengembangkan kemampuan di bidang pemrograman, struktur data, dan algoritma.
    </div>
  </div>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
