/*****************************************
  *----------------------------------
  |  ThisStyleVersion: 1.0.0      |
  |  ﾂｩ 2021-2023 By Pusyuu       |
  |  LastUpdate: 2023-07-05       |
  |  (^U^)PusyuuVueDesu           |
----------------------------------*
******************************************/

new Vue({
  el: '#app',
  data() {
    return {
      cards: [
        {
          new: true,
          image: "./catalog_img/app_image3.png",
          imageAlt: "カタログイメージ",
          date: "2023-06-06",
          title: "顔文字制作機",
          description: "このアプリでは、顔文字に使いそうなお好みの文字をパーツごとに入力するだけで簡単に顔文字を自作することができます。",
          link: "./catalog_page/kao"
        },
        {
          new: false,
          image: "./catalog_img/app_image2.png",
          imageAlt: "カタログイメージ",
          date: "2023-06-06",
          title: "カレンダー、時報付き時計",
          description: "このカレンダー、時報付き時計は、その名の通りカレンダーを見ながら時計を確認できてしまうアプリで30分と60分の時報付き時計なのです。",
          link: "./catalog_page/cal"
        },
        {
          new: false,
          image: "./catalog_img/app_image1.png",
          imageAlt: "カタログイメージ",
          date: "2023-06-06",
          title: "プシューアプリ",
          description: "このプシューアプリは、プシューや他の便利なサイトが埋め込まれていてまるでアプリを使用してるみたいに様々な機能を楽しむことができます。",
          link: "./catalog_page/papp"
        },
        // Add more card objects here...
      ]
    };
  }
});