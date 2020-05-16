<template>
  <div class="full">
    <Header></Header>

    <div class="info">

      <div class="game">
        <div class="card">
          <div class="card-image">
            <figure class="image is-4by3">
              <img src="https://bulma.io/images/placeholders/1280x960.png" alt="Placeholder image">
            </figure>
          </div>

          <div class="content">
            <strong>PvP: Player vs Player</strong> <br></br>
            プレーヤー同士でバトル！ <br></br>
            リンク＝＝＝＞<a href="http://localhost:3000/pvp">PvP</a>

          </div>
        </div>
        <div class="card">
          <div class="card-image">
            <figure class="image is-4by3">
              <img src="https://bulma.io/images/placeholders/1280x960.png" alt="Placeholder image">
            </figure>
          </div>

          <div class="content">
            <strong>PvE: Player vs Enemy</strong> <br></br>
            みんなで協力してモンスターを倒せ！ <br></br>
            リンク＝＝＝＞<a href="http://localhost:3000/pvp">PvE</a>
          </div>
        </div>
        <div class="card">
          <div class="card-image">
            <figure class="image is-4by3">
              <img src="https://bulma.io/images/placeholders/1280x960.png" alt="Placeholder image">
            </figure>
          </div>

          <div class="content">
            <strong>アスレ: アスレッチック</strong> <br></br>
            激ムズコースが10コース以上！<br></br>
            リンク＝＝＝＞<a href="http://localhost:3000/pvp">アスレ</a>
          </div>
        </div>
        <div class="card">
          <div class="card-image">
            <figure class="image is-4by3">
              <img src="https://bulma.io/images/placeholders/1280x960.png" alt="Placeholder image">
            </figure>
          </div>

          <div class="content">
            <strong>生活サーバー: お金をためて生活しよう</strong> <br></br>
            みんなでのんびりマイクラ生活！<br></br>
            リンク＝＝＝＞<a href="http://localhost:3000/pvp">生活 </a>
          </div>
        </div>

      </div>
    </div>
  </div>
</template>

<script>
import Header from "~/components/Header"
export default {
  name: "Index",
  components: { Header },
}
</script>

<style>

.info{
  width: 100%;
  background-image: linear-gradient(to right, #000000, #1a1419, #25232f, #273547, #1c495b, #1c495b, #1c495b, #1c495b, #273547, #25232f, #1a1419, #000000);
}

.card{
  width: 18%;
  display: inline-block;
  margin: 14px;
  padding: 1px;
  border-radius: 3px;
}

.game{
  display: inline-block;
  width: 100%;
}

.content{
  text-align: center;
  font-size: 15px;
}

</style>
