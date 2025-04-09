<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>ABF Global Exports</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f9f9f9;
      color: #333;
    }
    header {
      background-color: #004080;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      background-color: #003060;
      padding: 10px 20px;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 10px;
      font-weight: bold;
    }
    .lang-switch {
      cursor: pointer;
      color: #fff;
    }
    .container {
      padding: 20px;
    }
    .section {
      margin-bottom: 40px;
    }
    h2 {
      color: #004080;
    }
    .download-buttons a {
      display: inline-block;
      margin: 10px;
      padding: 10px 15px;
      background-color: #004080;
      color: white;
      text-decoration: none;
      border-radius: 5px;
    }
    footer {
      background-color: #003060;
      color: white;
      text-align: center;
      padding: 20px;
    }
  </style>
  <script>
    function switchLanguage(lang) {
      const elements = document.querySelectorAll("[data-en], [data-de]");
      elements.forEach(el => {
        el.textContent = el.getAttribute(`data-${lang}`);
      });
    }
  </script>
</head>
<body>
  <header>
    <h1 data-en="ABF Global Exports" data-de="ABF Global Exporte">ABF Global Exports</h1>
    <p data-en="Trusted Supplier of Medical & Surgical Equipment" data-de="Zuverlässiger Anbieter für medizinische und chirurgische Ausrüstung">
      Trusted Supplier of Medical & Surgical Equipment
    </p>
  </header>  <nav>
    <div>
      <a href="#about" data-en="About" data-de="Über Uns">About</a>
      <a href="#products" data-en="Products" data-de="Produkte">Products</a>
      <a href="#download" data-en="Brochures" data-de="Broschüren">Brochures</a>
      <a href="#contact" data-en="Contact" data-de="Kontakt">Contact</a>
    </div>
    <div class="lang-switch">
      <span onclick="switchLanguage('en')">EN</span> | <span onclick="switchLanguage('de')">DE</span>
    </div>
  </nav>  <div class="container">
    <section id="about" class="section">
      <h2 data-en="About Us" data-de="Über Uns">About Us</h2>
      <p data-en="We export high-quality medical and surgical equipment from India to Europe and Africa, including walkstands, hospital beds, and more."
         data-de="Wir exportieren hochwertige medizinische und chirurgische Ausrüstung aus Indien nach Europa und Afrika, darunter Gehhilfen, Krankenhausbetten und vieles mehr.">
         We export high-quality medical and surgical equipment from India to Europe and Africa, including walkstands, hospital beds, and more.
      </p>
    </section><section id="products" class="section">
  <h2 data-en="Product Categories" data-de="Produktkategorien">Product Categories</h2>
  <ul>
    <li data-en="Mobility Aids: Walkstands, wheelchairs, crutches" data-de="Mobilitätshilfen: Gehhilfen, Rollstühle, Krücken">Mobility Aids: Walkstands, wheelchairs, crutches</li>
    <li data-en="Surgical Equipment: Scalpels, clamps, forceps" data-de="Chirurgische Ausrüstung: Skalpelle, Klemmen, Pinzetten">Surgical Equipment: Scalpels, clamps, forceps</li>
    <li data-en="Hospital Essentials: Beds, stretchers, monitors" data-de="Krankenhausbedarf: Betten, Tragen, Monitore">Hospital Essentials: Beds, stretchers, monitors</li>
  </ul>
</section>

<section id="download" class="section">
  <h2 data-en="Download Brochures" data-de="Broschüren Herunterladen">Download Brochures</h2>
  <div class="download-buttons">
    <a href="#" download>Company Profile (EN)</a>
    <a href="#" download>Company Profile (DE)</a>
    <a href="#" download>Product Catalog (EN)</a>
    <a href="#" download>Product Catalog (DE)</a>
  </div>
</section>

<section id="contact" class="section">
  <h2 data-en="Contact Us" data-de="Kontaktieren Sie Uns">Contact Us</h2>
  <p>Email: info@abfglobalexports.com</p>
  <p>Phone/WhatsApp: +91-XXXXXXXXXX</p>
  <p>Location: India</p>
</section>

  </div>  <footer>
    <p>&copy; 2025 ABF Global Exports. All rights reserved.</p>
  </footer>
</body>
</html>
