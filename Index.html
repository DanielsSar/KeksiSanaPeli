<!DOCTYPE html>
<html>
<head>
  <title>Keksi sana -peli</title>
  <style>
    body { font-family: sans-serif; text-align: center; padding: 20px; }
    button { padding: 10px 20px; font-size: 16px; margin: 5px; }
    #pisteet div { margin: 10px 0; }
    #tulos { margin: 20px; font-size: 22px; }
  </style>
</head>
<body>

  <h1>Keksi sana -peli</h1>

  <div id="aloitus">
    <label>Kuinka monta pelaajaa?</label><br>
    <input type="number" id="pelaajamaara" min="1" max="10" value="2">
    <br><br>
    <button onclick="aloitaPeli()">Aloita peli</button>
  </div>

  <div id="peli" style="display:none;">
    <div id="tulos"></div>
    <button onclick="arvoPeli()">Arvo uusi kirjain ja kategoria</button>

    <h2>Pisteet:</h2>
    <div id="pisteet"></div>
  </div>

  <script>
    const kirjaimet = "ABCDEFGHIJKLMNOPQRSTUVWXYZ".split("");
    const kategoriat = [
      "eläin", "kaupunki", "kasvi", "esine", "ammatti", "maa", "ruoka", "laulu", "elokuva", "väri"
    ];

    let pisteet = [];

    function aloitaPeli() {
      const maara = parseInt(document.getElementById("pelaajamaara").value);
      pisteet = Array(maara).fill(0);
      const pisteDiv = document.getElementById("pisteet");
      pisteDiv.innerHTML = "";

      for (let i = 0; i < maara; i++) {
        const pelaajaDiv = document.createElement("div");
        pelaajaDiv.id = `pelaaja-${i}`;
        pelaajaDiv.innerHTML = `
          Pelaaja ${i+1}: <span id="piste-${i}">0</span> pistettä 
          <button onclick="lisaaPiste(${i})">+1 piste</button>
        `;
        pisteDiv.appendChild(pelaajaDiv);
      }

      document.getElementById("aloitus").style.display = "none";
      document.getElementById("peli").style.display = "block";
      arvoPeli();
    }

    function arvoPeli() {
      const kirjain = kirjaimet[Math.floor(Math.random() * kirjaimet.length)];
      const kategoria = kategoriat[Math.floor(Math.random() * kategoriat.length)];
      document.getElementById("tulos").innerHTML = `Kirjain: <b>${kirjain}</b><br>Kategoria: <b>${kategoria}</b>`;
    }

    function lisaaPiste(i) {
      pisteet[i]++;
      document.getElementById(`piste-${i}`).innerText = pisteet[i];
    }
  </script>

</body>
</html>
<style>
  body {
    font-family: sans-serif;
    text-align: center;
    padding: 20px;
    background: linear-gradient(to bottom, #f0f8ff, #d0e8ff);
  }
  button {
    padding: 10px 20px;
    font-size: 16px;
    margin: 5px;
    border: none;
    border-radius: 8px;
    background-color: #4CAF50;
    color: white;
  }
  button:hover {
    background-color: #45a049;
  }
  #pisteet div {
    margin: 10px auto;
    background-color: #ffffffaa;
    border-radius: 10px;
    padding: 10px;
    max-width: 300px;
    box-shadow: 2px 2px 6px #888888;
  }
  #tulos {
    margin: 20px;
    font-size: 24px;
    background-color: #fff;
    display: inline-block;
    padding: 15px 25px;
    border-radius: 10px;
    box-shadow: 1px 1px 8px #888888;
  }
</style>
