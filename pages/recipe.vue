<template>
  <div class="container text-center my-5">
    <h1>世界と日本の車</h1>
  </div>

  <div class="card mb-3 mx-auto">
    <div class="row g-0">
      <div class="col-md-6">
        <h1>世界で一番値段が高い車</h1>
        <div class="container mb-6">
          <div class="row gx-5">
            <div class="col-sm">
              <h2>メルセデスベンツ 300slr ウーレンハウトクーペ</h2>
              <img src="https://preview.free3d.com/img/2018/11/2399374330313049397/jafz01by.jpg"
                class="img-fluid rounded-start" alt="...">
            </div>
          </div>
        </div>
        <div class="row row-cols-1 row-cols-sm-2 row-cols-md-4">
          <div class="col border p-2">
            <div class="mb-6"><span class="badge bg-secondary">1</span></div>
            <p>オークションで1億3500万ユーロ（約213億1000万円）という破格の値段で落札された</p>
          </div>
          <div class="col border p-2">
            <div class="mb-6"><span class="badge bg-secondary">2</span></div>
            <p>"SLR"はドイツ語でSport, Leicht, Rennwagen（スポーツ・軽量・レーシングカー）をあらわす</p>
          </div>
        </div>
      </div>

      <div class="col-md-6">
        <h1>日本で一番値段が高い車</h1>
        <div class="container mb-6">
          <div class="row gx-5">
            <div class="col-sm">
              <h2>レクサスLFA</h2>
              <img src="https://img.amiami.jp/images/product/main/231/TOY-SCL3-53269.jpg"
                class="img-fluid rounded-start" alt="...">
            </div>
          </div>
        </div>
        <div class="row row-cols-1 row-cols-sm-2 row-cols-md-4">
          <div class="col border p-2">
            <div class="mb-2"><span class="badge bg-secondary">1</span></div>
            <p>価格は3750万円（ニュルブルクリンクパッケージは約4500万円）</p>
          </div>
          <div class="col border p-2">
            <div class="mb-2"><span class="badge bg-secondary">2</span></div>
            <p>最高速度は320km/h</p>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div class="container mb-5">
    <h1>日本で一番売れた車（2023年）</h1>
    <div class="row gx-5">
      <div class="col-sm">
        <h3>登録車で１位はトヨタ「ヤリス」</h3>
        <img src="https://www.weins-toyota-kanagawa.co.jp/file/cms/13701/3124628/image.jpg"
          class="img-fluid rounded-start" alt="...">
        <div class="row row-cols-1 row-cols-sm-2 row-cols-md-4">
          <div class="col border p-2">
            <div class="mb-2"><span class="badge bg-secondary">1</span></div>
            <p>販売台数19万4364台</p>
          </div>
          <div class="col border p-2">
            <div class="mb-2"><span class="badge bg-secondary">2</span></div>
            <p>2020年から4年連続でトップ</p>
          </div>
        </div>
      </div>
    </div>
    <div class="row gx-5">
      <div class="col-sm">
        <h3>軽四輪車で１位はホンダ「N-BOX」</h3>
        <img src="https://tjniigata.jp/assets/uploads/2022/01/NBOX-760x503.jpg"
          class="img-fluid rounded-start" alt="...">
        <div class="row row-cols-1 row-cols-sm-2 row-cols-md-4">
          <div class="col border p-2">
            <div class="mb-2"><span class="badge bg-secondary">1</span></div>
            <p>販売台数23万1385台</p>
          </div>
          <div class="col border p-2">
            <div class="mb-2"><span class="badge bg-secondary">2</span></div>
            <p>ホンダ「N-BOX」が唯一20万台超えの販売台数を記録して1位となった</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
const data = useRecipe()
</script>