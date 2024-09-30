<!DOCTYPE html>
<html>

<head>
  <title>INPUT DATA KE SPREAD SHEET</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    /*  */
    body {
      background-color: #0c0a0a;
    }
    #form-container {
      width: 500px;
      margin: 0 auto;
      background-color: #f1f1f7;
      border: 2px solid #da0808;
      border-radius: 10px;
      padding: 20px;
    }
    #form-container h2 {
      text-align: center;
      color: #1E90FF;
    }
    #form-container input[type="text"], #form-container input[type="date"], #form-container input[type="tel"] {
      width: 100%;
      padding: 10px;
      margin-bottom: 20px;
      border: 2px solid #f1d0d0;
      border-radius: 5px;
    }
    #form-container input[type="submit"] {
      background-color: #1E90FF;
      color: #FFFFFF;
      border: none;
      border-radius: 5px;
      padding: 10px;
      cursor: pointer;
    }
    #form-container input[type="submit"]:hover {
      background-color: #004B8D;
    }
    #footer {
      text-align: center;
      margin-top: 30px;
      font-size: 12px;
      color: #f7f1f1;
    }
  </style>
</head>

<body>
  <div id="form-container">
    <h2>INPUT DATA KE SPREAD SHEET</h2>
    <!-- akses link script app -->
    <form action="https://script.google.com/macros/s/AKfycbxn6lApgAR4svZx81TG7NyU6Q4E9zrE0WtAvs4ZdnpH0qJcjLkg8Cx3LM5yPDJSQrcr9g/exec" method="post">
    <!-- end akses  -->

        <label for="nama">Nama:</label>
      <input type="text" id="nama" name="nama" required>
      <label for="ktp">Nomor KTP:</label>
      <input type="text" id="ktp" name="ktp" required>
      <label for="tgl_lahir">Tanggal Lahir:</label>
      <input type="date" id="tgl_lahir" name="tgl_lahir" required>
      <label for="alamat">Alamat:</label>
      <input type="text" id="alamat" name="alamat" required>
      <label for="no_hp">Nomor HP:</label>
      <input type="tel" id="no_hp" name="no_hp" pattern="[0-9]{10,12}" required>
      <input type="submit" value="Simpan Data">
    </form>
  </div>

  <div id="footer">
    All Tutorial for you, jagan lupa subcribe karna akan selalu ada update
  </div>

</body>
</html>
