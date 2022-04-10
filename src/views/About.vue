<template>
  <div class="profile">
    <main>
      <aside class="profile-aside">
        <div>1234rw</div>
      </aside>
      <div class="profile-main">
        <div>main</div>
      </div>
    </main>
  </div>
</template>

<script>
import '@/assets/css/common.css';

export default {
  name: 'ProfileView',
};
</script>

<style scoped>
.profile {
  width: 100%;
  height: 100%;
  background: var(--smoky-black);
}

main {
  margin: 15px 12px;
  margin-bottom: 75px;
  min-width: 259px;
}

.profile-aside {
  position: sticky;
  top: 60px;
  max-height: max-content;
  height: 100%;
  margin-bottom: 0;
  padding-top: 60px;
  z-index: 1;
}

.profile-main {
  min-width: 75%;
  width: 75%;
  margin: 0;
}

@media (min-width: 1250px) {
}
</style>
