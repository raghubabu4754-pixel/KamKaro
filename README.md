<!DOCTYPE html>
<html lang="hi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>KaamKaro - Online Jobs</title>
<style>
body{margin:0;font-family:Arial;background:#f4f7fb;color:#222}
header{background:linear-gradient(135deg,#2563eb,#7c3aed);color:white;text-align:center;padding:30px 15px}
h1{margin:0;font-size:32px}
.container{max-width:700px;margin:auto;padding:20px}
.card{background:white;padding:20px;margin:15px 0;border-radius:16px;box-shadow:0 3px 12px #ddd}
.job{border:1px solid #ddd;padding:16px;margin:12px 0;border-radius:12px}
button{background:#2563eb;color:white;border:0;padding:12px 20px;border-radius:8px;font-weight:bold}
</style>
</head>

<body>

<header>
<h1>KaamKaro 💼</h1>
<p>घर बैठे ऑनलाइन काम और जॉब खोजें</p>
</header>

<div class="container">

<div class="card">
<h2>ऑनलाइन काम की तलाश है?</h2>
<p>यहाँ अलग-अलग ऑनलाइन काम और जॉब की जानकारी देखें।</p>
</div>

<div class="card">
<h2>Available Jobs</h2>

<div class="job">
<h3>💬 Chat Support</h3>
<p>घर बैठे ऑनलाइन चैट सपोर्ट का काम।</p>
<button onclick="apply('Chat Support')">Apply Now</button>
</div>

<div class="job">
<h3>⌨️ Data Entry</h3>
<p>ऑनलाइन डेटा एंट्री से जुड़ा काम।</p>
<button onclick="apply('Data Entry')">Apply Now</button>
</div>

<div class="job">
<h3>📱 Social Media Work</h3>
<p>Instagram और YouTube के लिए ऑनलाइन काम।</p>
<button onclick="apply('Social Media Work')">Apply Now</button>
</div>

</div>
</div>

<script>
function apply(job){
  let name=prompt("अपना नाम लिखें:");
  if(!name)return;

  let message=
  "नमस्ते, मुझे KaamKaro पर "+job+
  " के लिए आवेदन करना है। मेरा नाम "+name+" है।";

  window.open(
    "https://wa.me/917080838977?text="+encodeURIComponent(message),
    "_blank"
  );
}
</script>

</body>
</html>
