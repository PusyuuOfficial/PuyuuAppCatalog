/*****************************************
  *----------------------------------
  |  ThisStyleVersion: 1.0.2      |
  |  ﾂｩ 2021-2023 By Pusyuu       |
  |  LastUpdate: 2023-10-03       |
  |  License: MIT License         |
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
          title: "顔文字作成機",
          link: "./catalog_page/kao"
        },
        {
          new: false,
          image: "./catalog_img/app_image2.png",
          imageAlt: "カタログイメージ",
          date: "2023-06-06",
          title: "カレンダー、時報付き時計",
          link: "./catalog_page/cal"
        },
        {
          new: false,
          image: "./catalog_img/app_image1.png",
          imageAlt: "カタログイメージ",
          date: "2023-06-06",
          title: "プシューマルチアプリ",
          link: "./catalog_page/papp"
        },
        // Add more card objects here...
      ]
    };
  }
});