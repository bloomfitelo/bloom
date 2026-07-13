<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bloom Fit Elo</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Poppins:wght@400;500;600&display=swap');
        
        * { margin: 0; padding: 0; box-sizing: border-box; }
        
        body {
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(135deg, #f8d7e8 0%, #e8c4d8 100%);
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #5a3d4a;
            padding: 20px;
        }
        
        .container {
            max-width: 420px;
            width: 100%;
            text-align: center;
            background: rgba(255, 255, 255, 0.88);
            backdrop-filter: blur(12px);
            border-radius: 28px;
            padding: 40px 24px;
            box-shadow: 0 15px 35px rgba(180, 100, 140, 0.25);
        }
        
        .logo {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 6px solid #e8b4d0;
            margin: 0 auto 20px;
            object-fit: cover;
            box-shadow: 0 10px 25px rgba(200, 120, 160, 0.3);
        }
        
        h1 {
            font-family: 'Playfair Display', serif;
            font-size: 32px;
            color: #c06c84;
            margin-bottom: 6px;
        }
        
        .slogan {
            font-size: 18px;
            color: #d88aa8;
            margin-bottom: 24px;
            font-style: italic;
        }
        
        .bio {
            font-size: 15.5px;
            line-height: 1.6;
            color: #6b4e5a;
            margin-bottom: 32px;
            padding: 0 10px;
        }
        
        .links {
            display: flex;
            flex-direction: column;
            gap: 14px;
            margin-bottom: 40px;
        }
        
        .link {
            background: rgba(240, 200, 220, 0.9);
            color: #5a3d4a;
            text-decoration: none;
            padding: 17px 20px;
            border-radius: 50px;
            font-weight: 600;
            transition: all 0.3s ease;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 12px;
            font-size: 16.5px;
            box-shadow: 0 4px 12px rgba(200, 120, 160, 0.2);
        }
        
        .link:hover {
            background: #f8c4d8;
            transform: translateY(-4px);
        }
        
        .stripe-btn {
            background: linear-gradient(135deg, #635bff, #7b6eff);
            color: white;
            font-weight: 700;
            padding: 18px 20px;
            border-radius: 50px;
            text-decoration: none;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
            font-size: 17px;
            box-shadow: 0 6px 20px rgba(99, 91, 255, 0.3);
        }
        
        .stripe-btn:hover {
            transform: translateY(-4px);
            box-shadow: 0 10px 25px rgba(99, 91, 255, 0.4);
        }
        
        .testimonials {
            margin-top: 30px;
            padding-top: 30px;
            border-top: 1px solid #e8c4d8;
        }
        
        .testimonial {
            background: #fff9fb;
            padding: 18px;
            border-radius: 20px;
            margin-bottom: 16px;
            font-size: 14.5px;
            text-align: left;
            box-shadow: 0 4px 12px rgba(0,0,0,0.05);
        }
        
        .testimonial p {
            font-style: italic;
            color: #6b4e5a;
        }
        
        .author {
            margin-top: 8px;
            font-size: 13px;
            color: #c06c84;
            font-weight: 500;
        }
        
        .footer {
            margin-top: 40px;
            font-size: 13px;
            color: #b88aa0;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Ton logo -->
        <img src="https://via.placeholder.com/150/ffe4f0/000000?text=🌸" 
             alt="Bloom Fit Elo" class="logo">
        
        <h1>Bloom Fit Elo</h1>
        <p class="slogan">Deviens la meilleure version de toi-même 💫</p>
        
        <p class="bio">
            Bien-être • Nutrition • Lifestyle • Développement personnel<br><br>
            Rendre le bien-être simple, visuel et actionnable 🌸
        </p>
        
        <div class="links">
            <a href="#" target="_blank" class="link">🌿 Routines bien-être quotidiennes</a>
            <a href="#" target="_blank" class="link">📖 E-books & Mini-guides</a>
            <a href="#" target="_blank" class="link">📅 Trackers d’habitudes à imprimer</a>
            <a href="#" target="_blank" class="link">🍃 Ressources Nutrition & Mindset</a>
            <a href="#" target="_blank" class="link">💌 Newsletter douce</a>
            <a href="mailto:bloomfitelo@gmail.com" class="link">✉️ Me contacter</a>
        </div>
        
        <!-- Bouton Stripe -->
        <a href="https://buy.stripe.com/ton_lien_stripe_ici" target="_blank" class="stripe-btn">
            💖 Soutenir / Acheter mes guides
        </a>
        
        <!-- Avis clients -->
        <div class="testimonials">
            <h3 style="margin-bottom: 20px; color: #c06c84;">Ce que disent mes abonnées</h3>
            
            <div class="testimonial">
                <p>« Les trackers m’ont vraiment aidée à créer une routine douce et réaliste. Je me sens plus alignée ! »</p>
                <div class="author">— Sophie L.</div>
            </div>
            
            <div class="testimonial">
                <p>« Des contenus remplis de bienveillance. Enfin une approche qui ne me met pas la pression. Merci Elo ! »</p>
                <div class="author">— Marie T.</div>
            </div>
            
            <div class="testimonial">
                <p>« Les e-books sont magnifiques et ultra clairs. J’ai déjà imprimé mon tracker et je l’utilise tous les jours. »</p>
                <div class="author">— Julie D.</div>
            </div>
        </div>
        
        <div class="footer">
            Tout en douceur et clarté • Bloom Fit Elo ©
        </div>
    </div>
</body>
</html>