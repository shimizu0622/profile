<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
    <div class="container">
      <NuxtLink class="navbar-brand" to="/">ポートフォリオ</NuxtLink>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <NuxtLink class="nav-link" to="/profile">プロフィール</NuxtLink>
          </li>
          <li class="nav-item">
            <NuxtLink class="nav-link" to="/future-goals">今後の目標</NuxtLink>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>