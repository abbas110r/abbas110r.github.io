# abbas110r.github.io
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <style>
      @media screen and (max-width: 767px) {
        body {
          width: 90vw;
          height: 70vh;
          margin: auto;
        }
        .container {
          margin: auto;
          display: flex;
          flex-direction: column;
          justify-content: space-evenly;
          align-items: center;
        }
        img {
          width: 100%;
        }
        .box {
          box-shadow: 20px 20px 10px lightgray;
        }
      }
      @media screen and (min-width: 768px) and (max-width: 1023px) {
        body {
          width: 90vw;
          height: 70vh;
          margin: auto;
        }
        .container {
          display: grid;
          grid-template-columns: 50fr 50fr;
          grid-template-rows: 50fr 50fr;
          justify-items: stretch;
          align-items: stretch;
          column-gap: 0.2rem;
          row-gap: 0.2rem;
        }
        img {
          width: 100%;
        }
        .box {
          box-shadow: 20px 20px 10px lightgray;
        }
      }
      @media screen and (min-width: 1024px) {
        .container {
          height: 90vh;
          width: 70vw;
          margin: auto;
          column-gap: 0.3rem;
          row-gap: 0.3rem;
          display: grid;
          grid-template-rows: 25fr 25fr 25fr 25fr;
          grid-template-columns: 25fr 25fr 25fr;
          justify-items: stretch;
          align-items: stretch;
        }
        img {
          width: 100%;
          height: 100%;
          border-radius: 2%;
        }
        .one {
          grid-column: 2/4;
          grid-row: 1/3;
        }
        .box {
          box-shadow: 20px 20px 10px lightgray;
        }
      }
    </style>
  </head>
  <body>
    <div class="container">
      <div class="box">
        <img src="photo-1418479631014-8cbf89db3431.jpeg" alt="1" />
      </div>
      <div class="box one">
        <img src="photo-1421167418805-7f170a738eb4.jpeg" alt="2" />
      </div>
      <div class="box">
        <img src="photo-1433155805822-ffc337821a5b.jpeg" alt="3" />
      </div>
      <div class="box">
        <img src="photo-1441861539200-6208cf4a122f.jpeg" alt="4" />
      </div>
      <div class="box">
        <img src="photo-1453614512568-c4024d13c247.jpeg" alt="5" />
      </div>
      <div class="box">
        <img src="photo-1460400355256-e87506dcec4f.jpeg" alt="6" />
      </div>
      <div class="box">
        <img src="photo-1471253387723-35c53c9f97ca.jpeg" alt="7" />
      </div>
      <div class="box">
        <img src="photo-1475296204602-08d15839e95f.jpeg" alt="8" />
      </div>
      <div class="box">
        <img src="photo-1490990813269-10586274747f.jpeg" alt="9" />
      </div>
    </div>
  </body>
</html>
