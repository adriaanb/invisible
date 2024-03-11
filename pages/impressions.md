---
layout: page
title: Impressions
sidebar_sort_order: 4
sidebar_link: true
---

### re:publica 22

<div class="image-container">
  <img src="impressions/republica/001.jpg" alt="Image 001" class="responsive-image" onclick="openModal(this.src)">
  <!-- Add all images up to 011 -->
  <img src="impressions/republica/002.jpg" alt="Image 002" class="responsive-image" onclick="openModal(this.src)">
  <img src="impressions/republica/003.jpg" alt="Image 003" class="responsive-image" onclick="openModal(this.src)">
  <img src="impressions/republica/004.jpg" alt="Image 004" class="responsive-image" onclick="openModal(this.src)">
  <img src="impressions/republica/005.jpg" alt="Image 005" class="responsive-image" onclick="openModal(this.src)">
  <img src="impressions/republica/006.jpg" alt="Image 006" class="responsive-image" onclick="openModal(this.src)">
  <img src="impressions/republica/007.jpg" alt="Image 007" class="responsive-image" onclick="openModal(this.src)">
  <img src="impressions/republica/008.jpg" alt="Image 008" class="responsive-image" onclick="openModal(this.src)">
  <img src="impressions/republica/009.jpg" alt="Image 009" class="responsive-image" onclick="openModal(this.src)">
  <img src="impressions/republica/010.jpg" alt="Image 010" class="responsive-image" onclick="openModal(this.src)">
  <img src="impressions/republica/011.jpg" alt="Image 011" class="responsive-image" onclick="openModal(this.src)">
</div>
<div id="myModal" class="modal" onclick="closeModal()">
    <span class="close" onclick="closeModal()">&times;</span>
    <img class="modal-content" id="img01" onclick="event.stopPropagation()"> <!-- Prevent closing when clicking on the image -->
</div>
<script>
function openModal(src) {
    document.getElementById("myModal").style.display = "block";
    document.getElementById("img01").src = src;
}
function closeModal() {
    document.getElementById("myModal").style.display = "none";
}
// Close modal when clicking anywhere on the background
window.onclick = function(event) {
    var modal = document.getElementById("myModal");
    if (event.target == modal) {
        closeModal();
    }
}
</script>

