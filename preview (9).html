
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>QRBar Pro - QR & Barcode Generator</title>

<script src="https://cdnjs.cloudflare.com/ajax/libs/qrcodejs/1.0.0/qrcode.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jsbarcode/3.11.6/JsBarcode.all.min.js"></script>

<style>
:root {
  --bg:#090d18;
  --card:#141b2c;
  --border:#29344d;
  --accent:#7057ff;
  --text:#f5f7ff;
  --muted:#aab6cc;
}
*{box-sizing:border-box}
body{
  margin:0;background:var(--bg);color:var(--text);
  font-family:Arial,Helvetica,sans-serif
}
header{
  text-align:center;padding:25px 15px;
  background:linear-gradient(120deg,#4f46e5,#a21caf);
}
header h1{margin:0;font-size:30px}
header p{margin:8px 0 0;color:#eee}
main{max-width:1100px;margin:24px auto;padding:0 14px}
.layout{display:grid;grid-template-columns:1fr 1fr;gap:18px}
.card{
  background:var(--card);border:1px solid var(--border);
  border-radius:16px;padding:20px;min-width:0
}
h2{font-size:20px;margin:0 0 16px}
h3{font-size:16px;margin:18px 0 10px}
label{display:block;margin:13px 0 6px;font-size:14px;color:#d5dced}
input,textarea,select{
  width:100%;padding:12px;border:1px solid #394763;
  border-radius:9px;background:#0b1220;color:white;
  font-size:15px;outline:none
}
input:focus,textarea:focus,select:focus{border-color:#8b7aff}
input[type=color]{height:45px;padding:4px}
textarea{min-height:80px;resize:vertical}
button{
  border:0;border-radius:9px;padding:12px 15px;
  background:var(--accent);color:white;font-weight:bold;
  font-size:14px;cursor:pointer
}
button:hover{filter:brightness(1.13)}
.secondary{background:#293750}
.buttons{display:flex;flex-wrap:wrap;gap:9px;margin-top:16px}
#preview{
  min-height:280px;background:#fff;border-radius:12px;
  padding:15px;display:flex;align-items:center;
  justify-content:center;overflow:auto
}
#preview canvas,#preview img,#preview svg{
  max-width:100%;height:auto
}
.hidden{display:none!important}
.note{font-size:13px;color:var(--muted);line-height:1.6}
#status{font-size:14px;line-height:1.5;margin-top:12px;color:#86efac}
pre{
  white-space:pre-wrap;overflow-wrap:anywhere;
  background:#0b1220;color:#b9f7d0;padding:12px;
  border-radius:8px;max-height:230px;overflow:auto;font-size:12px
}
#encoded{min-height:130px}
.small{font-size:12px;color:var(--muted);line-height:1.5}
@media(max-width:760px){
  .layout{grid-template-columns:1fr}
  header h1{font-size:25px}
  .card{padding:15px}
}
</style>
</head>
<body>

<header>
  <h1>▣ QRBar Pro</h1>
  <p>QR Code & Barcode Generator</p>
</header>

<main>
<div class="layout">

<section class="card">
  <h2>1. Enter Your Details</h2>

  <label>Generation Type</label>
  <select id="mode" onchange="changeMode()">
    <option value="combined">Combined QR — All Details in One</option>
    <option value="text">Text / Website QR</option>
    <option value="wifi">Wi-Fi Connection QR</option>
    <option value="whatsapp">WhatsApp QR</option>
    <option value="facebook">Facebook QR</option>
    <option value="barcode">Barcode</option>
  </select>

  <!-- Combined QR fields -->
  <div id="combinedFields">
    <h3>Personal & Contact Details</h3>

    <label>Full Name</label>
    <input id="name" placeholder="Enter your name">

    <label>Phone Number</label>
    <input id="phone" type="tel" placeholder="+92 300 1234567">

    <label>WhatsApp Number</label>
    <input id="whatsapp" type="tel" placeholder="923001234567">

    <label>Email Address</label>
    <input id="email" type="email" placeholder="you@example.com">

    <label>Facebook Profile / Page URL</label>
    <input id="facebook" type="url" placeholder="https://facebook.com/yourpage">

    <label>Website URL</label>
    <input id="website" type="url" placeholder="https://example.com">

    <h3>Wi-Fi Details</h3>

    <label>Wi-Fi Network Name (SSID)</label>
    <input id="ssid" placeholder="Your Wi-Fi name">

    <label>Wi-Fi Password</label>
    <input id="wifiPassword" placeholder="Your Wi-Fi password">

    <label>Wi-Fi Security</label>
    <select id="security">
      <option value="WPA">WPA / WPA2</option>
      <option value="WEP">WEP</option>
      <option value="nopass">No Password</option>
    </select>

    <h3>Other Details</h3>

    <label>Address / Business Name / Notes</label>
    <textarea id="extra" placeholder="Write any additional information"></textarea>
  </div>

  <!-- Text QR -->
  <div id="textFields" class="hidden">
    <label>Text or Website URL</label>
    <textarea id="plainText" placeholder="Enter text, a link, or other information"></textarea>
  </div>

  <!-- WiFi QR -->
  <div id="wifiFields" class="hidden">
    <label>Wi-Fi Network Name</label>
    <input id="singleSSID" placeholder="Wi-Fi name">

    <label>Wi-Fi Password</label>
    <input id="singlePassword" placeholder="Wi-Fi password">

    <label>Security Type</label>
    <select id="singleSecurity">
      <option value="WPA">WPA / WPA2</option>
      <option value="WEP">WEP</option>
      <option value="nopass">No Password</option>
    </select>
  </div>

  <!-- WhatsApp QR -->
  <div id="whatsappFields" class="hidden">
    <label>WhatsApp Number (include country code)</label>
    <input id="singleWhatsApp" type="tel" placeholder="923001234567">

    <label>Optional Message</label>
    <textarea id="waMessage" placeholder="Hello!"></textarea>
  </div>

  <!-- Facebook QR -->
  <div id="facebookFields" class="hidden">
    <label>Facebook Profile / Page URL</label>
    <input id="singleFacebook" type="url" placeholder="https://facebook.com/yourpage">
  </div>

  <!-- Barcode -->
  <div id="barcodeFields" class="hidden">
    <label>Barcode Text / Number</label>
    <input id="barcodeValue" placeholder="Enter text or numbers">

    <label>Barcode Format</label>
    <select id="barcodeFormat">
      <option value="CODE128">Code 128</option>
      <option value="CODE39">Code 39</option>
      <option value="EAN13">EAN-13</option>
    </select>
  </div>

  <h3>Design Settings</h3>

  <label>Code Color</label>
  <input id="qrColor" type="color" value="#111111">

  <label>Background Color</label>
  <input id="bgColor" type="color" value="#ffffff">

  <label>QR Size</label>
  <select id="qrSize">
    <option value="200">Small — 200px</option>
    <option value="280" selected>Medium — 280px</option>
    <option value="360">Large — 360px</option>
    <option value="500">Extra Large — 500px</option>
  </select>

  <div class="buttons">
    <button onclick="generate()">Generate</button>
    <button class="secondary" onclick="resetForm()">Clear All</button>
  </div>

  <p class="note">
    Combined QR includes all the details you fill in. Leave unused fields blank.
  </p>
  <div id="status" role="status"></div>
</section>

<section class="card">
  <h2>2. Generated Code</h2>

  <div id="preview">
    <span style="color:#333;text-align:center">
      Your QR code or barcode will appear here
    </span>
  </div>

  <div class="buttons">
    <button onclick="downloadPNG()">Download PNG</button>
    <button class="secondary" onclick="downloadSVG()">Download SVG</button>
    <button class="secondary" onclick="downloadHTML()">Download HTML</button>
    <button class="secondary" onclick="printCode()">Print / PDF</button>
  </div>

  <div class="output">
    <h3>3. Encoded Information</h3>
    <textarea id="encoded" readonly placeholder="Generated information appears here"></textarea>
    <div class="buttons">
      <button class="secondary" onclick="copyData()">Copy Data</button>
    </div>
  </div>

  <div class="output">
    <h3>4. HTML Code</h3>
    <pre id="htmlOutput">Generate a code to create its HTML snippet.</pre>
    <div class="buttons">
      <button class="secondary" onclick="copyHTML()">Copy HTML</button>
    </div>
  </div>

  <p class="small">
    Note: Downloaded QR images contain the encoded information. Combined QR
    information is read as one text record when scanned. Wi-Fi auto-connect
    works most reliably with the dedicated Wi-Fi QR mode.
  </p>
</section>

</div>
</main>

<script>
let currentType = "";
let currentData = "";
let currentSVG = "";
let currentPNG = "";

const $ = id => document.getElementById(id);
const val = id => $(id).value.trim();

function changeMode(){
  const mode = val("mode");

  $("combinedFields").classList.toggle("hidden", mode !== "combined");
  $("textFields").classList.toggle("hidden", mode !== "text");
  $("wifiFields").classList.toggle("hidden", mode !== "wifi");
  $("whatsappFields").classList.toggle("hidden", mode !== "whatsapp");
  $("facebookFields").classList.toggle("hidden", mode !== "facebook");
  $("barcodeFields").classList.toggle("hidden", mode !== "barcode");

  $("status").textContent = "";
}

function escapeWiFi(str){
  return String(str).replace(/([\\;,:"])/g, "\\$1");
}

function wifiPayload(ssid, password, security){
  const safeSSID = escapeWiFi(ssid);
  const safePassword = escapeWiFi(password);
  const passPart = security === "nopass" ? "" : "P:" + safePassword + ";";
  return "WIFI:T:" + security + ";S:" + safeSSID + ";" + passPart + ";";
}

function buildCombinedData(){
  const rows = [];

  const name = val("name");
  const phone = val("phone");
  const waRaw = val("whatsapp");
  const email = val("email");
  const facebook = val("facebook");
  const website = val("website");
  const ssid = val("ssid");
  const password = val("wifiPassword");
  const security = val("security");
  const extra = val("extra");

  if(name) rows.push("Name: " + name);
  if(phone) rows.push("Phone: " + phone);

  if(waRaw){
    const number = waRaw.replace(/\D/g, "");
    if(number) rows.push("WhatsApp: https://wa.me/" + number);
  }

  if(email) rows.push("Email: " + email);
  if(facebook) rows.push("Facebook: " + facebook);
  if(website) rows.push("Website: " + website);

  if(ssid){
    rows.push("Wi-Fi Network: " + ssid);
    rows.push("Wi-Fi Security: " + security);

    if(security !== "nopass" && password){
      rows.push("Wi-Fi Password: " + password);
    }

    rows.push("Wi-Fi Connection Payload: " +
      wifiPayload(ssid, password, security));
  }

  if(extra) rows.push("Additional Information: " + extra);

  return rows.join("\n");
}

function getQRData(){
  const mode = val("mode");

  if(mode === "combined"){
    return buildCombinedData();
  }

  if(mode === "text"){
    return val("plainText");
  }

  if(mode === "wifi"){
    const ssid = val("singleSSID");
    if(!ssid) throw new Error("Please enter the Wi-Fi network name.");
    const security = val("singleSecurity");
    return wifiPayload(ssid, val("singlePassword"), security);
  }

  if(mode === "whatsapp"){
    const number = val("singleWhatsApp").replace(/\D/g, "");
    if(!number) throw new Error("Please enter a WhatsApp number.");
    const message = val("waMessage");
    let url = "https://wa.me/" + number;
    if(message) url += "?text=" + encodeURIComponent(message);
    return url;
  }

  if(mode === "facebook"){
    const url = val("singleFacebook");
    if(!url) throw new Error("Please enter a Facebook URL.");
    if(!/^https?:\/\/(www\.)?facebook\.com\//i.test(url)){
      throw new Error("Enter a valid Facebook URL starting with https://facebook.com/");
    }
    return url;
  }

  return "";
}

function generate(){
  if(typeof QRCode === "undefined" || typeof JsBarcode === "undefined"){
    $("status").textContent = "Please check your internet connection and reload the page.";
    return;
  }

  const mode = val("mode");
  const preview = $("preview");
  $("status").textContent = "";
  preview.innerHTML = "";
  currentType = mode;
  currentData = "";
  currentSVG = "";
  currentPNG = "";
  $("encoded").value = "";
  $("htmlOutput").textContent = "";

  try{
    if(mode === "barcode"){
      const text = val("barcodeValue");
      const format = val("barcodeFormat");

      if(!text) throw new Error("Please enter barcode text or a number.");

      const svg = document.createElementNS("http://www.w3.org/2000/svg", "svg");
      preview.appendChild(svg);

      JsBarcode(svg, text, {
        format: format,
        lineColor: val("qrColor"),
        background: val("bgColor"),
        width: 2,
        height: 100,
        displayValue: true,
        margin: 10
      });

      currentSVG = new XMLSerializer().serializeToString(svg);
      currentData = text;
      $("encoded").value = text;
      $("htmlOutput").textContent =
        '<svg xmlns="http://www.w3.org/2000/svg">' +
        svg.innerHTML + "</svg>";

      $("status").textContent = "Barcode generated successfully.";
      return;
    }

    const data = getQRData();
    if(!data) throw new Error("Please fill in at least one field.");

    currentData = data;
    $("encoded").value = data;

    const size = Number(val("qrSize"));
    const host = document.createElement("div");
    preview.appendChild(host);

    new QRCode(host, {
      text: data,
      width: size,
      height: size,
      colorDark: val("qrColor"),
      colorLight: val("bgColor"),
      correctLevel: QRCode.CorrectLevel.L
    });

    setTimeout(() => {
      const canvas = host.querySelector("canvas");
      const image = host.querySelector("img");

      if(canvas){
        currentPNG = canvas.toDataURL("image/png");
      }else if(image){
        currentPNG = image.src;
      }

      if(currentPNG){
        $("htmlOutput").textContent =
          '<img alt="QR Code" src="' + currentPNG + '">';
      }
    }, 150);

    $("status").textContent =
      mode === "combined"
        ? "Combined QR generated. All entered details are inside this one QR code."
        : "QR code generated successfully.";

  }catch(error){
    preview.innerHTML = "";
    const msg = document.createElement("p");
    msg.style.cssText = "color:#b91c1c;text-align:center";
    msg.textContent = error.message || "Unable to generate code.";
    preview.appendChild(msg);
    $("status").textContent = "";
  }
}

function saveBlob(blob, filename){
  const url = URL.createObjectURL(blob);
  const a = document.createElement("a");
  a.href = url;
  a.download = filename;
  document.body.appendChild(a);
  a.click();
  a.remove();
  setTimeout(() => URL.revokeObjectURL(url), 1500);
}

function downloadPNG(){
  if(currentType === "barcode"){
    const svg = $("preview").querySelector("svg");
    if(!svg) return alert("Generate a barcode first.");
    downloadSVG();
    return;
  }

  const canvas = $("preview").querySelector("canvas");
  if(!canvas) return alert("Generate a QR code first.");

  const a = document.createElement("a");
  a.download = "qrbar-pro.png";
  a.href = canvas.toDataURL("image/png");
  a.click();
}

function downloadSVG(){
  if(currentType === "barcode"){
    const svg = $("preview").querySelector("svg");
    if(!svg) return alert("Generate a barcode first.");
    const copy = svg.cloneNode(true);
    copy.setAttribute("xmlns", "http://www.w3.org/2000/svg");
    const data = new XMLSerializer().serializeToString(copy);
    saveBlob(new Blob([data], {type:"image/svg+xml"}), "qrbar-barcode.svg");
    return;
  }

  const canvas = $("preview").querySelector("canvas");
  if(!canvas) return alert("Generate a QR code first.");

  const png = canvas.toDataURL("image/png");
  const svg =
    '<svg xmlns="http://www.w3.org/2000/svg" width="' + canvas.width +
    '" height="' + canvas.height + '">' +
    '<image width="100%" height="100%" href="' + png + '"/>' +
    '</svg>';

  saveBlob(new Blob([svg], {type:"image/svg+xml"}), "qrbar-code.svg");
}

function downloadHTML(){
  if(!currentData) return alert("Generate a code first.");

  let html = "";

  if(currentType === "barcode"){
    const svg = $("preview").querySelector("svg");
    if(!svg) return alert("Generate a barcode first.");
    const copy = svg.cloneNode(true);
    copy.setAttribute("xmlns", "http://www.w3.org/2000/svg");
    html = '<!DOCTYPE html><html><head><meta charset="UTF-8">' +
      '<title>QRBar Pro Barcode</title></head><body>' +
      new XMLSerializer().serializeToString(copy) +
      '</body></html>';
  }else{
    const canvas = $("preview").querySelector("canvas");
    if(!canvas) return alert("Please wait a moment and try again.");
    const png = canvas.toDataURL("image/png");
    html = '<!DOCTYPE html><html><head><meta charset="UTF-8">' +
      '<meta name="viewport" content="width=device-width,initial-scale=1">' +
      '<title>My QR Code</title></head><body style="font-family:Arial;text-align:center">' +
      '<h2>My QR Code</h2><img alt="QR Code" src="' + png +
      '"><p>Scan to read the encoded information.</p></body></html>';
  }

  saveBlob(new Blob([html], {type:"text/html"}), "my-qr-code.html");
}

async function copyData(){
  if(!currentData) return alert("Generate a code first.");
  await copyText(currentData);
}

async function copyHTML(){
  const html = $("htmlOutput").textContent;
  if(!html || html.startsWith("Generate")) return alert("Generate a code first.");
  await copyText(html);
}

async function copyText(text){
  try{
    await navigator.clipboard.writeText(text);
    alert("Copied successfully.");
  }catch(e){
    const ta = document.createElement("textarea");
    ta.value = text;
    document.body.appendChild(ta);
    ta.select();
    document.execCommand("copy");
    ta.remove();
    alert("Copied successfully.");
  }
}

function printCode(){
  const preview = $("preview");
  if(!preview.querySelector("canvas,svg,img")){
    return alert("Generate a code first.");
  }

  const win = window.open("", "_blank");
  if(!win) return alert("Please allow pop-ups to print.");

  const content = preview.innerHTML;
  win.document.open();
  win.document.write(
    '<!DOCTYPE html><html><head><title>Print QRBar Pro</title>' +
    '<style>body{font-family:Arial;text-align:center;padding:30px}' +
    'canvas,img,svg{max-width:100%;height:auto}</style></head><body>' +
    '<h2>QRBar Pro</h2>' + content + '</body></html>'
  );
  win.document.close();
  win.focus();
  setTimeout(() => win.print(), 300);
}

function resetForm(){
  document.querySelectorAll(
    'input:not([type="color"]),textarea'
  ).forEach(el => el.value = "");

  $("qrColor").value = "#111111";
  $("bgColor").value = "#ffffff";
  $("mode").value = "combined";
  $("qrSize").value = "280";
  $("security").value = "WPA";
  $("singleSecurity").value = "WPA";
  $("barcodeFormat").value = "CODE128";

  $("preview").innerHTML =
    '<span style="color:#333;text-align:center">Your QR code or barcode will appear here</span>';

  $("encoded").value = "";
  $("htmlOutput").textContent = "Generate a code to create its HTML snippet.";
  $("status").textContent = "";

  currentType = "";
  currentData = "";
  currentSVG = "";
  currentPNG = "";

  changeMode();
}

changeMode();
</script>
</body>
</html>
