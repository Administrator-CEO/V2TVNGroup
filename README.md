<html lang="vi">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>V2T VN Group</title>
    <style>
      * {
        box-sizing: border-box;
        margin: 0;
        padding: 0;
      }
      body {
        font-family: Arial, sans-serif;
        background-color: #f0f0f0;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
      }
      .slideshow-container {
        width: 100%;
        max-width: 600px;
        height: auto;
        margin: 20px auto;
        position: relative;
        overflow: hidden;
        display: flex;
        justify-content: center;
        align-items: center;
      }
      .slideshow-container img {
        width: 100%;
        height: auto;
        max-height: 400px;
        display: none;
        transition: opacity 0.5s ease-in-out;
        object-fit: cover;
      }
      .slideshow-container img.active {
        display: block;
      }
      .content {
        width: 100%;
        max-width: 800px;
        padding: 20px;
        background-color: #fff;
        border-radius: 12px;
        box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
      }
      .text-section {
        margin: 20px 0;
      }
    </style>
  </head>
  <body>
    <div class="content">
      <h1>
        <img
          src="https://i.pinimg.com/736x/89/76/68/897668015da396d4e09d8349b1b75d89.jpg"
          width="125"
        />V2T VN Group
      </h1>
      <hr />
    </div>
    <div class="slideshow-container">
      <img
        src=""
        alt=""
        class="active"
      />
    </div>
    <div>
      <div class="text-section">
        <h2>
          <img
            src="https://i.pinimg.com/474x/53/97/b8/5397b8513641e0cc484d88627ef32f13.jpg"
            width="50"
          />Otis Storyteller VN
        </h2>
        <li>
          Youtube:
          <a href="http://www.youtube.com/@OtisStorytellerVN" target="_blank"
            >http://www.youtube.com/@OtisStorytellerVN</a
          >
        </li>
        <br />
        <li>
          Facebook:
          <a href="https://www.facebook.com/OtisStorytellerVN" target="_blank"
            >https://www.facebook.com/OtisStorytellerVN</a
          >
        </li>
        <br />
        <li>
          TikTok:
          <a href="https://www.tiktok.com/@otisstorytellervn" target="_blank"
            >https://www.tiktok.com/@otisstorytellervn</a
          >
        </li>
        <hr />
      </div>
      <div class="text-section">
        <h2>
          <img
            src="https://i.pinimg.com/474x/1f/c5/cb/1fc5cb6ddcc227bef09e2c3ef7671d02.jpg"
            width="50"
          />Andy Music Offiial
        </h2>
        <li>
          Youtobe:
          <a href="https://www.youtube.com/@AndyMusicOfficiall" target="_blank"
            >https://www.youtube.com/@AndyMusicOfficiall</a
          >
        </li>
        <br />
        <li>
          Facebook:
          <a href="https://www.facebook.com/AndyMusicOfficiall" target="_blank"
            >https://www.facebook.com/AndyMusicOfficiall</a
          >
        </li>
        <br />
        <li>
          TikTok:
          <a href="https://www.tiktok.com/@andymusicofficial" target="_blank"
            >https://www.tiktok.com/@andymusicofficial</a
          >
        </li>
        <hr />
      </div>
      <div class="text-section">
        <h2>
          <img
            src="https://i.pinimg.com/474x/4b/71/e4/4b71e49ce03aa1808cd8ecf061e91c0d.jpg"
            width="50"
          />KOTG.Andy Gamer
        </h2>
        <li>
          Youtube:
          <a href="https://www.youtube.com/@KOTGTonyGamer" target="_blank"
            >https://www.youtube.com/@KOTGTonyGamer</a
          >
        </li>
        <br />
        <li>
          Facebook:
          <a href="https://www.facebook.com/KOTG.TonyGamer" target="_blank"
            >https://www.facebook.com/KOTG.TonyGamer</a
          >
        </li>
        <br />
        <li>
          TikTok:
          <a href="https://www.tiktok.com/@kotgtonygamer" target="_blank"
            >https://www.tiktok.com/@kotgtonygamer</a
          >
        </li>
        <hr />
      </div>
      <div class="text-section">
        <h2>Donate: MoMo - 0843840438</h2>
        <img
          src="https://i.pinimg.com/474x/d7/21/e4/d721e4e7121d86a03a5f8c57d0cc0e0e.jpg"
          alt=""
          width="250"
        />
        <br />
        <a>Click</a>
        <a href="https://me.momo.vn/1MIVTntVfOUBiBfAI8f1UV" target="_blank"
          >Vào Đây</a
        >
        <a>!</a> <br />
        <hr />
      </div>
      <div class="text-section">
        <a
          >Hotline: <a href="tel:0329022431" targer="_blank">0329022431</a>,
          <a href="tel:0843840438" target="_blank">0843840438</a></a
        ><br />
        <a
          >Email:
          <a
            href="mailto:chiefexecutiveofficer.v2t.vn@gmail.com?subject=Gửi Admin!"
            target="_blank"
            >chiefexecutiveofficer.v2t.vn@gmail.com</a
          >
        </a>
        <br />
        <a
          >Địa chỉ:
          <a
            href="https://maps.app.goo.gl/CuVh62Yj5EpAXLAw9"
            target="_blank"
            >2252/22/12. Tổ 2, Kp1, Quận 12, Hồ Chí Minh, Việt Nam</a
          ></a
        >
      </div>
    </div>
    <script>
      const images = document.querySelectorAll(".slideshow-container img");
      let currentIndex = 0;
      function changeImage() {
        images[currentIndex].classList.remove("active");
        currentIndex = (currentIndex + 1) % images.length;
        images[currentIndex].classList.add("active");
      }
      setInterval(changeImage, 5000);
    </script>
  </body>
</html>

