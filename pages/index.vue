<template>
  <div class="container">
    <div class="article">
      <a href="/street-photography-using-mobile-phone-camera">
        <img :src="require(`../assets/article-2/Picture3.jpg`)" alt="" />
        <h1>Street Photography using Mobile Phone Camera</h1>
        <h3>Mithun Saha</h3>
        <p>
          Photography is an art of vision that can be expressed through a bunch
          of pixels and hence should not always depend on high budget devices.
          Nowadays Smartphone has replaced cameras and other devices in many
          aspects of photography. It is because budget phones have decent
          cameras and can get you some amazing results. Though the camera and
          lens in your Smartphone isn’t as good as a professional digital
          camera, but in street photography, using a phone sometimes can be of
          advantage.
        </p>
        <span class="ul">Read Article</span>
      </a>
    </div>
    <div class="article">
      <a href="/photography-from-passion-to-profession">
        <h1>Photography: From Passion to Profession</h1>
        <h3>M Aminur Rahman</h3>
        <p>
          Human by nature, are passion driven. Think of a new born, in their
          toddler years, whatever they do, everyone cheers them up, every single
          move is welcomed with immense joy, every small step forward is
          recorded. As time passes by, priorities change, we are chasing that
          inevitable dream of maintaining social standards but where does
          passion lie by? Most of us, are lost in the race of life, we bury our
          passion and led by a life set up by the societal standards.
        </p>
        <span class="ul">Read Article</span>
      </a>
    </div>
    <div class="article">
      <a href="/mobile-photography-take-your-photography-to-the-next-level">
        <img :src="require(`../assets/article-3/Picture1.png`)" alt="" />
        <h1>Mobile Photography: Take your photography to the next level</h1>
        <h3>Numan Ahmed</h3>
        <p>
          Before the days of the smartphone, capturing a moment in real-time was
          not as easy as just pulling out a smartphone from your pocket.
          Nowadays, if you want to capture a moment in real-time, remember, the
          best camera is always in your pocket. But you are taking photos
          constantly with your smartphone and wondering why your photos don’t
          have that ‘WOW’ factor you see around on Instagram or somewhere else,
          is that all about you don’t have your own expensive camera?
        </p>
        <span class="ul">Read Article</span>
      </a>
    </div>
    <div class="article">
      <a
        class="bangla bangla-size-fix"
        href="/black-and-white-photography-and-subsequent"
      >
        <img :src="require(`../assets/article-4/Picture1.jpg`)" alt="" />
        <h1 style="font-size: 32px; line-height: 30px">
          সাদাকালো ছবি ও তৎ সম্পর্কিত অন্যান্য বিষয়াবলী
        </h1>
        <h3 class="regular-font">Samiran Chakraborty</h3>
        <h4 class="regular-font">Visual Artist</h4>
        <p>
          প্রথম ক্যামেরা আবিষ্কার হয় ১৮২০ এর দশকে। সেই সময়ের আগে মানুষ ছবি
          তোলার জন্য প্রচলিত মিডিয়াতগুলোর উপর নির্ভরশীল ছিল যেমন- চিত্রকর্ম,
          স্কেচ এবং অঙ্কন। যাইহোক, যখন ক্যামেরায় ছবি তোলা হয়েছিল তখন মনে
          হয়েছিল ঐতিহ্যবাহী মিডিয়াগুলির চেয়ে ক্যামেরার ছবি কোন বস্তু সম্পর্কে
          আরও তথ্যবহুল বা বিশদভাবে উপস্থাপন করেছিল।
        </p>
        <span class="ul regular-font">Read Article</span>
      </a>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>

<style lang="scss" scoped>
.container {
  margin-top: 20vh;
}

.article {
  margin: 1em 0;
  padding: 1em;
  background-color: rgba(0, 0, 0, 0.51);
}

img {
  padding: 1em 1em;
  width: 100%;
}
</style>