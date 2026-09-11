# 🛍️ Venkat Textiles E-Commerce Storefront

Venkat Textiles కోసం ప్రత్యేకంగా రూపొందించిన ఆధునిక ఇ-కామర్స్ వెబ్‌సైట్ మరియు ఆర్డర్ మేనేజ్‌మెంట్ సిస్టమ్. ఇందులో కస్టమర్లు బట్టల కలెక్షన్లను చూసి, కార్ట్‌కి యాడ్ చేసుకొని, రేజర్‌పే (Razorpay) ద్వారా సురక్షితంగా పేమెంట్ చేయవచ్చు.

## ✨ ఫీచర్లు (Features)
- **Modern UI:** Tailwind CSS తో డిజైన్ చేసిన రెస్పాన్సివ్ వెబ్‌సైట్.
- **Dynamic Catalog:** శారీలూ, డ్రెస్ మెటీరియల్స్ మరియు హ్యాండ్లూమ్స్ కేటగిరీ ఫిల్టర్లు.
- **Smart Cart System:** సులభంగా ఐటెమ్స్ యాడ్ మరియు రిమూవ్ చేసుకునే సదుపాయం.
- **Razorpay Integration:** కస్టమర్ల కోసం లైవ్ యూపీఐ (UPI), కార్డ్ పేమెంట్స్ సదుపాయం.
- **Shopify Sync Backend:** ఆర్డర్ విజయవంతం కాగానే షాపిఫై (Shopify) ఇన్వెంటరీ ఆటోమేటిక్‌గా అప్‌డేట్ అవుతుంది.

## 🛠️ టెక్ స్టాక్ (Tech Stack)
- **Frontend:** HTML5, Tailwind CSS, JavaScript
- **Backend:** Node.js, Express.js
- **Integrations:** Razorpay Payment Gateway, Shopify Admin & Storefront API

## 🚀 లోకల్‌గా రన్ చేయడం ఎలా? (Installation & Setup)

### 1. ప్రాజెక్ట్‌ను క్లోన్ చేయండి
```bash
git clone https://github.com
cd venkat-textiles
```

### 2. డిపెండెన్సీలను ఇన్‌స్టాల్ చేయండి
```bash
npm install express axios
```

### 3. ఎన్విరాన్మెంట్ వేరియబుల్స్ సెటప్ (.env)
ప్రాజెక్ట్ రూట్ ఫోల్డర్‌లో ఒక `.env` ఫైల్ క్రియేట్ చేసి మీ సీక్రెట్ కీస్ యాడ్ చేయండి:
```env
PORT=5000
RAZORPAY_WEBHOOK_SECRET=your_razorpay_secret
SHOPIFY_ADMIN_ACCESS_TOKEN=your_shopify_token
```

### 4. సర్వర్‌ను స్టార్ట్ చేయండి
```bash
node server.js
```
ఇప్పుడు మీ బ్యాకెండ్ సర్వర్ `http://localhost:5000` లో రన్ అవుతుంది. ఫ్రంటెండ్ కోసం `index.html` ఫైల్‌ను నేరుగా బ్రౌజర్‌లో ఓపెన్ చేయవచ్చు.

## 🔒 లైసెన్స్ (License)
ఈ ప్రాజెక్ట్ MIT లైసెన్స్ కింద ఉచితంగా అందుబాటులో ఉంది.
