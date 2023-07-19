/*****************************************
  *----------------------------------
  |  ThisStyleVersion: 1.0.1      |
  |  ﾂｩ 2021-2023 By Pusyuu       |
  |  LastUpdate: 2023-07-06       |
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
          title: "顔文字制作機",
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
          title: "プシューアプリ",
          link: "./catalog_page/papp"
        },
        // Add more card objects here...
      ]
    };
  }
});