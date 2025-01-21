<template>
  <div class="bg-dark text-light min-vh-100 d-flex align-items-center">
    <div class="container py-5">
      <div class="text-center">
        <h1 class="display-1 fw-bold mb-5">ポートフォリオ</h1>
        <p class="lead fs-3 mb-5">私のポートフォリオサイトにお越しいただき、ありがとうございます。 このサイトでは、私自身についてと将来の目標について紹介しています。</p>
        <div class="d-flex justify-content-center gap-4">
          <NuxtLink to="/profile" class="btn btn-primary btn-lg px-5 py-3">
            プロフィールを見る
          </NuxtLink>
          <NuxtLink to="/future-goals" class="btn btn-outline-light btn-lg px-5 py-3">
            目標を見る
          </NuxtLink>
        </div>
      </div>
    </div>
  </div>
</template>