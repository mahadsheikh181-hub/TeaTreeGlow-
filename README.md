<html lang="en">
 <head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Pure Nature - Tea Tree Serum</title>
 <style> 
    body { 
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; 
        margin: 0; padding: 0; 
        background: #0b0f0d; color: white; text-align: center; 
    }
    .header-wrapper {
        position: fixed; top: 0; width: 100%; z-index: 2000;
        box-shadow: 0 2px 10px rgba(0,0,0,0.5);
    }
   .banner { 
        background: #d90429; color:
   white; 
        padding: 6px; font-weight: bold; 
        font-size: 11px; /* Font chhota kiya */
        letter-spacing: 0.5px;
    }   header { 
        background: #1b4332; 
        padding: 10px 0; /* Padding kam ki */
        border-bottom: 2px solid #22c55e; 
    }
  header h2 {
        margin: 0; font-size: 18px; /* Likhawat chhoti ki */
        letter-spacing: 1px; font-weight: 800;
  /* Hero Banner Section */
    .hero-section {
        margin-top: 75px; /* Adjust for smaller header */
        padding: 60px 20px;
        background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)),                    
    url('https://i.postimg.cc/YCzn3Psq/1767535757518.jpg');
    background-size: cover; background-position: center;
        border-radius: 0 0 20px 20px;
    } .hero-section h1 { font-size: 28px; color: #22c55e; margin-bottom: 8px; }
    .hero-section p { font-size: 16px; opacity: 0.9; }
  .container { max-width: 450px; margin: auto; padding: 15px; }        
      /* Trust & Stock */
    .trust-banner { background: linear-gradient(90deg, #1b4332, #22c55e); padding: 12px; border-radius: 10px; margin: 15px 0; font-size: 14px; font-weight: bold; }
    .stock-container { background: #161b18; border-radius: 10px; padding: 12px; margin: 15px 0; border: 1px solid #2d3631; }
    .stock-bar { height: 8px; background: #333; border-radius: 4px; margin-top: 8px; overflow: hidden; }
    .stock-fill { height: 100%; background: #d90429; width: 8%; animation: pulse 1.5s infinite; }
  @keyframes pulse { 0% { opacity: 1; } 50% { opacity: 0.5; } 100% { opacity: 1; } } /* Price Box */
   .price-box { background: #161b18; padding: 20px; border-radius: 15px; border: 1px dashed #22c55e; margin: 20px 0; }
    .total-bill { font-size: 32px; color: #22c55e; font-weight: 900; margin-top: 10px; border-top: 1px solid #333; padding-top: 10px; 
                 /* Input Style */
    .input-box { width: 100%; padding: 14px; margin-bottom: 12px; border-radius: 8px; border: 1px solid #333; background: #000; color: white; font-size: 15px; box-sizing: border-box; } 
   /* Button */
    .btn { background: linear-gradient(180deg, #22c55e, #1b4332); color: white; padding: 18px; width: 100%; border: none; border-radius: 12px; font-size: 18px; font-weight: bold; cursor: pointer; 
   /* Reviews (Lambi List) */
    .review-card { background: #161b18; border: 1px solid #2d3631; border-radius: 12px; padding: 15px; margin-bottom: 12px; text-align: left; }
    .verified-tag { color: #22c55e; font-size: 10px; font-weight: bold; float: right; border: 1px solid #22c55e; padding: 2px 5px; border-radius: 4px; }
    .stars { color: #ffcc00; font-size: 12px; margin: 5px 0; }
    .review-text { font-style: italic; color: #ccc; font-size: 14px; margin: 5px 0; }
.sticky-footer { position: fixed; bottom: 0; left: 0; width: 100%; background: rgba(11, 15, 13, 0.98); padding: 12px; border-top: 1px solid #333; z-index: 1000; box-sizing: border-box; }
 </style>
</head>
<body>
 <div class="header-wrapper">
    <div class="banner"> 🔥 35% OFF + FREE GIFT TODAY! 🎁 </div> 
    <header><h2>PURE NATURE</h2></header>
 </div>

 <section class="hero-section">
    <h1>Tea Tree Serum</h1>
    <p>Get Clear, Glowing & Acne-Free Skin</p>
 </section>

 <div class="container">        
    <div class="trust-banner">🏆 50,000+ Happy Customers</div>
    
   <div class="stock-container">
        <span style="font-size:16px; color: #ff4d4d; font-weight: bold;">HURRY! ONLY 2 UNITS LEFT</span>
        <div class="stock-bar"><div class="stock-fill"></div></div>
    </div>

   <img src="https://i.postimg.cc/YCzn3Psq/1767535757518.jpg" style="width:100%; border-radius:15px; border:2px solid #22c55e; margin-bottom:20px;">

 <div class="price-box">
   <div style="text-decoration: line-through; color: #888; font-size:14px;">Original Price: Rs. 3,000</div>
   <div style="font-size: 18px;">Sale: Rs. 1,800 + Delivery</div>
        <div class="total-bill">TOTAL: RS. 2,000</div>
    </div>
 <div class="card" id="order-form">
        <h3 style="color:#22c55e; margin-bottom:15px;">Order Details</h3>
        <input type="text" id="custName" class="input-box" placeholder="Your Full Name">
   <input type="text" id="custAddress" class="input-box" placeholder="Full Address & City">
  <input type="tel" id="custPhone" class="input-box" placeholder="WhatsApp Number">
  <button class="btn" onclick="sendOrder()">Place Order Now ✅</button>
   </div>
   <h3 style="color:#22c55e; margin-top:40px; text-align:left; border-bottom: 1px solid #22c55e; padding-bottom:10px;">Customer Feedback</h3>
    <div id="reviews-list"></div>
    <div style="height: 100px;"></div>
 </div>

 <div class="sticky-footer">
    <button class="btn" style="padding: 12px;" onclick="document.getElementById('order-form').scrollIntoView({behavior: 'smooth'})">Order Now - Rs. 2,000</button>
 </div>

 <script>
    const reviews = [
        {n:"Ayesha K.", c:"Lahore", r:"Maine 1 week use kiya, pimples gayab ho gaye!"},
        {n:"Sana M.", c:"Karachi", r:"Best quality, skin boht fresh ho gayi hai."},
        {n:"Zeeshan A.", c:"Islamabad", r:"Original product, fast delivery. 10/10."},
        {n:"Hina B.", c:"Peshawar", r:"Dark spots light ho rahe hain, recommended!"},
        {n:"Mariam", c:"Multan", r:"Serum boht light hai, chip-chip nahi karta."},
        {n:"Saad A.", c:"Sialkot", r:"Achi packing thi, results bhi ache hain."},
        {n:"Fatima G.", c:"Quetta", r:"My skin feels glowing. Thanks Pure Nature!"},
        {n:"Bilal K.", c:"Rawalpindi", r:"Wife boht khush hain results dekh kar."},
        {n:"Nida P.", c:"Gujranwala", r:"Acne scars ke liye best serum hai."},
        {n:"Sara J.", c:"Hyderabad", r:"Delivery boht jaldi mil gayi, authentic product."},
        {n:"Kiran S.", c:"Faisalabad", r:"Best price mein itna acha product nahi milta."},
        {n:"Umer D.", c:"Sargodha", r:"Good for oily skin, results are amazing."},
        {n:"Iqra R.", c:"Jhelum", r:"Pores tight ho gaye hain, skin smooth lagti hai."},
        {n:"Maira W.", c:"Bahawalpur", r:"Original packing aur best results."},
        {n:"Zainab Q.", c:"Mardan", r:"Recommended for everyone having acne issues."},
        {n:"Tayyaba", c:"Sheikhupura", r:"Baqi sab products se ye sasta aur behtar hai."},
        {n:"Rimsha", c:"Okara", r:"Cooling effect hai, garmiyon ke liye best hai."}
        {n:"Ayesha K.", c:"Lahore", r:"Maine 1 week use kiya, pimples gayab ho gaye! Boht zabardast serum hai."},
        {n:"Sana M.", c:"Karachi", r:"Best quality, skin boht fresh ho gayi hai. Original product hai."},
        {n:"Zeeshan A.", c:"Islamabad", r:"Original product, fast delivery. 2 din mein mil gaya, packing bhi achi thi."},
        {n:"Hina B.", c:"Peshawar", r:"Dark spots light ho rahe hain, recommended for oily skin users."},
        {n:"Mariam", c:"Multan", r:"Serum boht light hai, chip-chip nahi karta. Garmiyo ke liye best hai."},
        {n:"Saad A.", c:"Sialkot", r:"Achi packing thi, results bhi jaldi mil gaye. 100% satisfied."},
        {n:"Fatima G.", c:"Quetta", r:"My skin feels glowing. Pehli bar koi product suit kiya hai face ko."},
        {n:"Bilal K.", c:"Rawalpindi", r:"Wife ke liye order kiya tha, wo results dekh kar boht khush hain."},
        {n:"Nida P.", c:"Gujranwala", r:"Acne scars ke liye best serum hai. Maine 2 aur order kar diye hain."},
        {n:"Sara J.", c:"Hyderabad", r:"Delivery boht jaldi mil gayi, authentic product aur affordable price."},
        {n:"Kiran S.", c:"Faisalabad", r:"Best price mein itna acha product nahi milta. Alhamdullilah result mil gaya."},
        {n:"Umer D.", c:"Sargodha", r:"Good for oily skin, results are amazing. Delivery bhi on time thi."},
        {n:"Iqra R.", c:"Jhelum", r:"Pores tight ho gaye hain, skin smooth lagti hai. 5 stars from my side."},
        {n:"Maira W.", c:"Bahawalpur", r:"Original packing aur best results. Pure Nature is doing a great job."},
        {n:"Zainab Q.", c:"Mardan", r:"Recommended for everyone having acne issues. Boht mild aur effective hai."},
        {n:"Tayyaba", c:"Sheikhupura", r:"Baqi sab products se ye sasta aur behtar hai. Result 100% hai."},
        {n:"Rimsha", c:"Okara", r:"Cooling effect hai, skin bilkul fresh ho jati hai lagane ke baad."},
        {n:"Sobia T.", c:"Rahim Yar Khan", r:"Best results in 5 days! Acne bilkul control ho gayi hai."},
        {n:"Amna L.", c:"Larkana", r:"Maine boht mehange serum try kiye par ye wala sab se best nikla."},
        {n:"Hafsa B.", c:"Sahiwal", r:"Fragrance boht achi hai aur skin soft ho gayi hai. Shukriya!"},
        {n:"Faiza V.", c:"Vehari", r:"Very fast delivery, 24 hours mein parcel mil gaya. Quality superb hai."},
        {n:"Tahira M.", c:"Mirpur", r:"Acne marks kafi purane thay, ab halkay hona shuru ho gaye hain."},
        {n:"Naila U.", c:"Haripur", r:"Skin oily hona band ho gayi hai jab se ye use kar rahi hoon."},
        {n:"Bushra E.", c:"Bhakkar", r:"Original product. Customer service bhi boht achi hai."},
        {n:"Sumaira K.", c:"Attock", r:"My favorite serum now! Face pe ek natural glow aa gaya hai."},
        {n:"Rabia Z.", c:"Chiniot", r:"Pimples ke liye is se behtar kuch nahi, wo bhi itni kam price mein."},
        {n:"Jaweria A.", c:"D.G. Khan", r:"Packing dekh kar hi lag raha tha original hai. Result bhi awesome hai."},
        {n:"Saba F.", c:"Kohat", r:"Zabardast product! 100% organic lag raha hai koi side effect nahi hua."}
    ];
    const list = document.getElementById('reviews-list');
    reviews.forEach(rev => {
        list.innerHTML += `
            <div class="review-card">
                <span class="verified-tag">Verified</span>
                <strong>${rev.n} <small style="color:#888;">— ${rev.c}</small></strong>
                <div class="stars">★★★★★</div>
                <p class="review-text">"${rev.r}"</p>
            </div>`;
    });
    function sendOrder() {
        const name = document.getElementById('custName').value;
        const addr = document.getElementById('custAddress').value;
        const ph = document.getElementById('custPhone').value;
        if(!name || !addr || !ph) { alert("Please fill all details!"); return; }
        const msg = `*NEW ORDER*%0A*Item:* Tea Tree Serum%0A*Name:* ${name}%0A*Phone:* ${ph}%0A*Address:* ${addr}%0A*Bill:* Rs 2000`;
        window.open("https://wa.me/923183757056?text=" + msg, "_blank");
    }
 </script>
</body>
</html>
