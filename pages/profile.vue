<template>
  <div class="bg-dark text-light min-vh-100 h-100">
    <div class="container py-5">
      <h1 class="text-center display-4 py-5">プロフィール</h1>
      
      <!-- 基本情報カード -->
      <div class="card bg-dark text-light border-light mb-5">
        <div class="card-body">
          <h2 class="card-title h3 mb-4">基本情報</h2>
          <div class="row g-4">
            <div class="col-md-6">
              <div class="mb-4">
                <h3 class="h5">氏名</h3>
                <p>清水晴斗</p>
              </div>
              <div class="mb-4">
                <h3 class="h5">職業</h3>
                <p>学生</p>
              </div>
            </div>
            <div class="col-md-6">
              <div class="mb-4">
                <h3 class="h5">年齢</h3>
                <p>19歳</p>
              </div>
              <div class="mb-4">
                <h3 class="h5">出身地</h3>
                <p>滋賀県</p>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- 経歴セクション -->
      <div class="mb-5">
        <div class="card bg-dark text-light border-light mb-5">
          <div class="card-body">
            <h3 class="card-title h4">過去</h3>
            <div class="mt-4">
              <h4 class="h6 text-light">小中高性時代</h4>
              <p>
              小中高と、スポーツに励んでいました。小学3年で地元のサッカースポーツ少年団に入り、４年間プレーしました。
              </p>
            
            </div>
          </div>
        </div>

        <!-- 今後の展望 -->
        <div class="card bg-dark text-light border-light ">
          <div class="card-body">
            <h3 class="card-title h4">今後の展望</h3>
            <div class="mt-4">
              <h4 class="h6 text-light">目指す方向性</h4>
              <ul class="list-unstyled ps-3">
                <li class="mb-2">・フルスタックエンジニアとしてのスキルアップ</li>
                <li class="mb-2">・新しい技術への積極的なキャッチアップ</li>
              </ul>

              <h4 class="h6 text-light mt-4">習得予定の技術</h4>
              <ul class="list-unstyled ps-3">
                <li class="mb-2">・クラウドインフラストラクチャ</li>
                <li class="mb-2">・AI/機械学習の基礎</li>
                <li class="mb-2">・セキュリティ関連知識</li>
              </ul>
            </div>
          </div>
        </div>
      </div>

      <!-- トップページに戻るボタン -->
      <div class="text-center mt-5 pb-5 mb-5">
        <NuxtLink to="/" class="btn btn-outline-light btn-lg">
          トップページに戻る
        </NuxtLink>
      </div>
    </div>
  </div>
</template>