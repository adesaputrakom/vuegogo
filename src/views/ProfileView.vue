<template>
  <div class="profile">
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-lg-6 text-start">
                <div class="d-flex">
                    <div class="flex-shrink-0">
                        <img src="../assets/adesaputra.jpeg" alt="Profile" class="user-pic">
                    </div>
                    <div class="flex-grow-1 ms-3">
                        <h5>Ade Saputra</h5>
                        <p>This is some content from a media component. You can replace this with any content and adjust it as needed.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
  </div>
</template>

<script>

import 'bootstrap/dist/css/bootstrap.css';

export default {
  name: 'ProfileView',
  components: {

  }
}
</script>

<style scoped>
    .user-pic {
        border-radius: 200%;
        height: 80px;
        width: 80px;
    }
</style>
