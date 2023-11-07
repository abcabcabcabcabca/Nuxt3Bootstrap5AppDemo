<template>
  <div class="container text-center my-5">
    <h1>{{ data.title }}</h1>
    <div class="alert alert-primary" role="alert">{{ data.description }}</div>
  </div>
  <div class="container mb-5">
    <div class="card mb-3 mx-auto">
      <div class="row g-0">
        <div class="col-md-4">
          <img
            src="https://toyota.jp/pages/contents/top/image/pr_area/crown/crown_pc_1.jpg"
            class="img-fluid rounded-start" alt="...">
        </div>
        <div class="col-md-8">
          <div class="card-body">
            <h5 class="card-title">{{data.zairyo}}</h5>
            <div class="card-text">
              <ul>
                <li v-for="item in data.material">{{ item.text }}</li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="container mb-5">
    <h2>CENTURY</h2>
    <div class="row row-cols-1 row-cols-sm-2 row-cols-md-4">
      <div class="col border p-2">
        <div class="mb-2"><span class="badge bg-secondary">1</span></div>
        <p>☆をボウルに混ぜ合わせておく。</p>
      </div>
      <div class="col border p-2">
        <div class="mb-2"><span class="badge bg-secondary">2</span></div>
        <p>別のボウルに★を全て混ぜ合わせておく。</p>
      </div>
      <div class="col border p-2">
        <div class="mb-2"><span class="badge bg-secondary">3</span></div>
        <p>肉の厚みがある部分を切り開き、厚みを一定にする。<br />鶏肉１枚を２～３等分の大きめに切る。</p>
      </div>
      <div class="col border p-2">
        <div class="mb-2"><span class="badge bg-secondary">4</span></div>
        <p>１のボウルに鶏肉を浸す。(時間があれば20分以上浸す。)</p>
      </div>
      <div class="col border p-2">
        <div class="mb-2"><span class="badge bg-secondary">5</span></div>
        <p>２のボウルに鶏肉を入れて粉類をまんべんなくまぶし、別の容器に並べていく。<br />
          粉が余るようでしたら、二度付けをお勧めします！</p>
      </div>
      <div class="col border p-2">
        <div class="mb-2"><span class="badge bg-secondary">6</span></div>
        <p>卵液→粉→卵液→粉と二度付けする事で、カリっと感がアップ＋味もしっかり付きます！写真の我が家のは二度付けしています。</p>
      </div>
      <div class="col border p-2">
        <div class="mb-2"><span class="badge bg-secondary">7</span></div>
        <p>油を160度に温める。<br />
          (温めるのはこのタイミングで大丈夫です。待ってる間に衣が鶏肉になじみます。)</p>
      </div>
      <div class="col border p-2">
        <div class="mb-2"><span class="badge bg-secondary">8</span></div>
        <p>160度で５分以上、様子を見ながら、火が通ったら、一度上げて、今度は180～200度でカリっと仕上げ、完成です☆</p>
      </div>
      <div class="col border p-2">
        <div class="mb-2"><span class="badge bg-secondary">9</span></div>鶏肉の1枚はサイズにばらつきがある為、2～3枚という記載に変更しました。
      </div>

    </div>
    <ol>

    </ol>
  </div>
  <div class="container mb-5">
    <div class="row gx-5">
      <div class="col-sm">
        <h3>VELLFIRE</h3>

        <p>

毎日の移動を、アグレシッブに。
圧倒的な力強さと極上の快適さに
心が昂ぶる、大空間サルーン。

力強さと心地よさを両立した動的性能
移動の快適さを極めた後席空間
周囲を圧倒するエクステリアデザイン
</p>
      </div>
      <div class="col-sm">
        <h3>ALPHARD</h3>

        <p>

一歩先へ進化を遂げた究極のもてなし空間。
隅々に行き渡る快適さが、
あらゆる移動をくつろぎに変えていく。

おもてなし装備に満ちた後席空間
上質を磨き上げたエクステリアデザイン
大切な人を守り抜く安全性能
　　　　</p>
      </div>
    </div>
  </div>
</template>
<script setup>
 const data = useRecipe()
</script>

