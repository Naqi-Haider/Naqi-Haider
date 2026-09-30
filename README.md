<div align="center"> 
<img src="https://media4.giphy.com/media/v1.Y2lkPTZjMDliOTUybG80Z2U1ZWhrNDB2ZmlwcGFsN28zcHVvZ2hiNjhjdWczejgxb2k1NiZlcD12MV9naWZzX3NlYXJjaCZjdD1n/DSxKEQoQix9hC/source.gif" height="160" width="auto" />
  
# Hi, I'm Naqi Haider  
### Full-Stack Developer (MERN) | Shopify Theme Developer  

 Building scalable web apps & high-performance eCommerce experiences  
 Interested in MERN Stack & Shopify theme customization  

---

export default {
 async fetch(req, env) {
   const n = parseInt((await env.COUNTER.get("views")) || "0") + 1;
   await env.COUNTER.put("views", String(n));
   const svg = `<svg xmlns="http://www.w3.org/2000/svg" width="130" height="20">
     <rect width="80" height="20" fill="#555"/><rect x="80" width="50" height="20" fill="#007ec6"/>
     <g fill="#fff" font-family="Verdana" font-size="11">
       <text x="6" y="14">Profile Views</text><text x="86" y="14">${n}</text></g></svg>`;
   return new Response(svg, { headers: {
     "Content-Type": "image/svg+xml",
     "Cache-Control": "no-cache, no-store" } });
 }
};

</div>

---

## About Me

I’m a **Full-Stack Developer** mainly working with the **MERN stack** and **Shopify theme development**.  
I love building complex and innovative Web applications. I am still a beginner at this phase but someday my GitHub will be filled with exciting projects :)

-  MERN Stack (MongoDB, Express, React, Node.js)
-  Shopify Theme Development (Liquid, Custom Sections)
-  Focused on performance, UX & maintainable code
-  Always learning and improving

---

<div align="center">
  <h3>My Tech Stack</h3>
  <img src="https://skillicons.dev/icons?i=js,react,nodejs,express,mongodb,html,css,tailwind,shopify,git,linux,docker,postman" />
</div>

---

## ⭐ Support My Work

If you like my work:
- ⭐ Star repositories  
- 🤝 Follow me on GitHub  
- 💬 Reach out for collaboration or freelance work

> _“Don’t give up!  Anything worth doing is going to be a struggle at some point, but you can succeed if you just keep trying.” <br>-Kimberly Brehm_

---
