<template>
  <nav>
    <div class="flex-container">
      <h1>moebook</h1>
      <div class="flex-container space-between">
        <ul class="flex-container">
          <li>Home</li>
          <li>Friends</li>
          <li>Posts</li>
        </ul>
        <p>Profile Icon</p>
      </div>
      <hr />
    </div>
  </nav>
</template>
  
<style scoped>
  h1 {
    color: var(--main-header-color);
    padding-left: 1em;
  }
  .flex-container {
    display: flex;
    align-items: center;
    gap: 1rem;
  }
  .space-between {
    justify-content: space-between;
    flex: 1;
  }
</style>
  