<template>
  <section class="download">
    <div class="container">
      <h1>Download ANCS</h1>
      <p>Click the button below to download the application.</p>

      <a :href="downloadLink">
        <button class="download-btn">
          Download Now
        </button>
      </a>
    </div>
  </section>
</template>

<script>
export default {
  name: "DownloadPage",
  data() {
    return {
      // 🔥 حط هنا لينك GitHub Releases بتاعك
      downloadLink: "https://github.com/username/repo/releases/download/v1.0/ANCS.exe"
    };
  }
};
</script>

<style scoped>
.download {
  text-align: center;
  padding: 100px 20px;
}

.container {
  max-width: 600px;
  margin: auto;
}

h1 {
  font-size: 36px;
  margin-bottom: 20px;
}

p {
  font-size: 18px;
  margin-bottom: 30px;
  color: #555;
}

.download-btn {
  background-color: #42b983;
  color: white;
  border: none;
  padding: 15px 30px;
  font-size: 18px;
  border-radius: 8px;
  cursor: pointer;
  transition: 0.3s;
}

.download-btn:hover {
  background-color: #369870;
}
</style>