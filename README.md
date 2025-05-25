<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Wrzucanie zdjęć</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 2rem;
      background: #f9f9f9;
    }
    h1 {
      color: #333;
    }
    .upload-container {
      border: 2px dashed #aaa;
      padding: 2rem;
      text-align: center;
      background: white;
    }
    .upload-container:hover {
      border-color: #555;
    }
    input[type="file"] {
      margin-top: 1rem;
    }
    .preview {
      margin-top: 2rem;
      display: flex;
      flex-wrap: wrap;
      gap: 1rem;
    }
    .preview img {
      max-width: 200px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    .qr-code {
      margin-top: 3rem;
      text-align: center;
    }
  </style>
</head>
<body>
  <h1>Wrzucanie zdjęć</h1>
  <div class="upload-container">
    <p>Wybierz zdjęcia do przesłania:</p>
    <input type="file" id="fileInput" accept="image/*" multiple />
  </div>

  <div class
# zdj-cia
