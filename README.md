<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Majallad.com</title>
    <style>
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            background-color: #000000; /* Black background for the rest of the page */
        }

        /* Header Banner Wrapper */
        .header {
            position: relative;
            width: 100%;
            height: 300px; /* Adjust the height to fit your image */
        }

        /* Banner Image */
        .header img.banner {
            width: 100%;
            height: 100%;
            object-fit: contain; /* Prevent cropping and ensure the full image fits */
            display: block;
        }

        /* Overlay Elements (Logo & Text) */
        .overlay {
            position: absolute;
            top: 50%; /* Align text vertically in the middle */
            left: 20px; /* Space from left side for logo */
            width: 100%;
            text-align: left;
            color: white;
            transform: translateY(-50%); /* Adjusts for perfect vertical centering */
        }

        /* Logo */
        .logo {
            width: 80px; /* Smaller logo size */
            height: auto;
            display: inline-block;
        }

        /* Text (Majallad.com) */
        .header-text {
            font-family: 'Impact', sans-serif; /* Rugged, bold font */
            font-size: 24px; /* Smaller text size */
            color: white;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.6); /* Contrast for readability */
            letter-spacing: 3px;
            margin-left: 10px; /* Space between logo and text */
        }

        /* Content Section */
        .content {
            padding: 20px 40px; /* Add padding to the left and right */
            color: white;
        }

        /* About Me Section */
        .about-me {
            padding: 40px 20px;
            color: white;
            display: flex;
            align-items: center;
        }

        /* Scrolling Images Section */
        .photo-album {
            overflow: hidden;
            white-space: nowrap;
            width: 100%;
        }

        .scrolling-images {
            display: inline-block;
            animation: scroll 20s linear infinite;
        }

        .photo {
            display: inline-block;
            width: 30%;
            margin-right: 20px;
        }

        @keyframes scroll {
            0% {
                transform: translateX(0%);
            }
            100% {
                transform: translateX(-50%);
            }
        }
    </style>
</head>
<body>

    <!-- Header Banner Section -->
    <div class="header">
        <!-- Replace with your image for the banner -->
        <img src="C:\Users\default.LAPTOP-07KBR12J\Pictures\Screenshots\Screenshot (2).png" alt="Header Banner" class="banner">
        
        <!-- Overlay for Logo and Text -->
        <div class="overlay">
            <!-- Logo (Replace with your actual logo file) -->
            <img src="C:\Users\default.LAPTOP-07KBR12J\Pictures\Timur Textiles Logo (Black Background).jpg" class="logo">
            
            <!-- Text -->
            <div class="header-text">Majallad.com</div>
        </div>
    </div>

    <!-- Content Below Banner (Black Background) -->
    <div class="content">
        <h1 style="text-align: center;">Hadiths To Remember</h1>
        
        <!-- Hadiths Section One -->
        <section>
            <p>1. Abdullah ibn Al-Harith ibn Hazm said, “I have never seen anyone who smiles more than the Prophet does.” (At-Tirmidhi)</p>
            <p>2. Jarir ibn Abdullah said: “Allah’s Messenger (peace and blessings be upon him) never refused me permission to see him since I embraced Islam and never looked at me but with a smile” (Sahih Muslim).</p>
            <p>3. Abu Dhar narrated from the Prophet that he said, “Do not disdain a good deed, (no matter how small it may seem) even if it is your meeting with your brother with a cheerful face” (Sahih Muslim).</p>
            <p>4. And, the Prophet (peace be upon him) said, “Smiling in your brother’s face is an act of charity” (At-Tirmidhi)</p>
        </section>

        <!-- Hadiths Section Two -->
        <section>
            <p>1. Surah Al Mu’minun Ayah 111

إِنِّى جَزَيْتُهُمُ ٱلْيَوْمَ بِمَا صَبَرُوٓا۟ أَنَّهُمْ هُمُ ٱلْفَآئِزُونَ

Indeed, I have rewarded them this Day for their patient endurance – that they are the attainers [of success].</p>
            <p>2. Jarir ibn Abdullah said: “Allah’s Messenger (peace and blessings be upon him) never refused me permission to see him since I embraced Islam and never looked at me but with a smile” (Sahih Muslim).</p>
            <p>3. Abu Dhar narrated from the Prophet that he said, “Do not disdain a good deed, (no matter how small it may seem) even if it is your meeting with your brother with a cheerful face” (Sahih Muslim).</p>
            <p>4. And, the Prophet (peace be upon him) said, “Smiling in your brother’s face is an act of charity” (At-Tirmidhi)</p>
        </section>
    </div>

    <!-- Display Logo Section -->
    <section class="photo-album">
        <h2 style="text-align: center;">أَشْهَدُ أَنْ لَا إِلَٰهَ إِلَّا ٱللَّٰهُ مُحَمَّدٌ رَسُولُ ٱللَّٰهِ</h2>
        <div class="scrolling-images">
            <!-- Images -->
            <div class="photo">
                <img src="C:\Users\default.LAPTOP-07KBR12J\Pictures\Timur Textiles Logo (Blue Background).jpg" alt="Image 2" style="width: 100%; height: auto; border-radius: 10px;">
            </div>
            <div class="photo">
                <img src="C:\Users\default.LAPTOP-07KBR12J\Pictures\Timur Textiles Logo (Yellow Background).jpg" alt="Image 1" style="width: 100%; height: auto; border-radius: 10px;">
            </div>
            <div class="photo">
                <img src="C:\Users\default.LAPTOP-07KBR12J\Pictures\Timur Textiles Logo (Teal Background).jpg" alt="Image 6" style="width: 100%; height: auto; border-radius: 10px;">
            </div>
            <div class="photo">
                <img src="C:\Users\default.LAPTOP-07KBR12J\Pictures\Timur Textiles Logo (Red Background).jpg" alt="Image 3" style="width: 100%; height: auto; border-radius: 10px;">
            </div>
            <div class="photo">
                <img src="C:\Users\default.LAPTOP-07KBR12J\Pictures\Timur Textiles Logo (Green Background).jpg" alt="Image 4" style="width: 100%; height: auto; border-radius: 10px;">
            </div>
            <div class="photo">
                <img src="C:\Users\default.LAPTOP-07KBR12J\Pictures\Timur Textiles Logo (Pink Background).jpg" alt="Image 5" style="width: 100%; height: auto; border-radius: 10px;">
            </div>
            <!-- Duplicate images for seamless scrolling -->
            <div class="photo">
                <img src="C:\Users\default.LAPTOP-07KBR12J\Pictures\Timur Textiles Logo (Blue Background).jpg" alt="Image 2" style="width: 100%; height: auto; border-radius: 10px;">
            </div>
            <div class="photo">
                <img src="C:\Users\default.LAPTOP-07KBR12J\Pictures\Timur Textiles Logo (Yellow Background).jpg" alt="Image 1" style="width: 100%; height: auto; border-radius: 10px;">
            </div>
            <div class="photo">
                <img src="C:\Users\default.LAPTOP-07KBR12J\Pictures\Timur Textiles Logo (Teal Background).jpg" alt="Image 6" style="width: 100%; height: auto; border-radius: 10px;">
            </div>
            <div class="photo">
                <img src="C:\Users\default.LAPTOP-07KBR12J\Pictures\Timur Textiles Logo (Red Background).jpg" alt="Image 3" style="width: 100%; height: auto; border-radius: 10px;">
            </div>
            <div class="photo">
                <img src="C:\Users\default.LAPTOP-07KBR12J\Pictures\Timur Textiles Logo (Green Background).jpg" alt="Image 4" style="width: 100%; height: auto; border-radius: 10px;">
            </div>
            <div class="photo">
                <img src="C:\Users\default.LAPTOP-07KBR12J\Pictures\Timur Textiles Logo (Pink Background).jpg" alt="Image 5" style="width: 100%; height: auto; border-radius: 10px;">
            </div>
        </div>
    </section>

<h1 style="font-size: 40px; font-weight: bold; text-align: center; margin-bottom: 20px; color: #0073e6;">Oriental Rugs in a Shifting Landscape</h1>
<div style="width: 100%; padding: 20px; box-sizing: border-box;">
  <div style="display: flex; align-items: flex-start; gap: 20px;">
    <img src="C:\Users\default.LAPTOP-07KBR12J\Pictures\Carpet 1.jpg" alt="Oriental Rug" style="width: 300px; height: 300px; object-fit: cover; border-radius: 8px;">
    <div style="max-width: 600px;">
      <h2 style="font-size: 32px; font-weight: bold; margin: 0 0 20px 0;">Oriental Rugs in a Shifting Landscape</h2>
      <p style="font-size: 16px; color: #333; line-height: 1.6; margin-bottom: 10px;">
        In the wake of the Taliban’s return to power in 2021, the Oriental rug industry has faced unprecedented challenges. Political upheaval and disrupted trade routes have left many traditional rug weavers in Afghanistan grappling with uncertainty. Supply chains that once flowed seamlessly are now riddled with delays, while economic instability has put immense pressure on artisans who have spent generations perfecting their craft. This turbulent climate has cast a shadow over an industry known not just for its functional value but for its rich cultural heritage.
      </p>

      <p style="font-size: 16px; color: #333; line-height: 1.6; margin-bottom: 10px;">
        Traditional Afghan weavers are at a crossroads. With restricted access to international markets and diminishing financial stability, many artisans have been forced to adapt or risk losing their time-honored skills. The delicate art of hand-knotting Oriental rugs, with its intricate patterns and vibrant symbolism, is suffering as a result of these new economic and political realities. The challenges faced by these craftspeople call for innovative solutions that can safeguard their legacy while meeting modern market demands.
      </p>

      <p style="font-size: 16px; color: #333; line-height: 1.6; margin-bottom: 10px;">
        Enter <strong>Timur Textiles</strong>—a beacon of hope and the change the industry so desperately needs. Led by Ethan Derrick, <a href="https://www.TimurTextiles.com" target="_blank" style="color: #0073e6; text-decoration: none; font-weight: bold;">TimurTextiles.com</a> is an online vendor that goes beyond traditional commerce. Ethan himself travels extensively, meeting with carpet weavers on the ground to understand their challenges firsthand and forge genuine relationships. His commitment to supporting the artisans not only ensures that these skilled weavers receive fair compensation, but also that their timeless craft is preserved and promoted to a global audience. In an era of instability, Ethan’s personal touch and dedication signal a much-needed shift in how the industry operates.
      </p>

      <p style="font-size: 16px; color: #333; line-height: 1.6; margin-bottom: 10px;">
        <strong>Timur Textiles</strong> isn’t just another rug seller—it represents a transformative approach to a traditional craft. By working directly with weavers, Ethan Derrick has established a model that bridges the gap between ancient artistry and contemporary business practices. His hands-on involvement means that every rug offered by <a href="https://www.TimurTextiles.com" target="_blank" style="color: #0073e6; text-decoration: none; font-weight: bold;">TimurTextiles.com</a> is not only a work of art but also a testament to sustainable and ethical trade. This innovative approach has helped stabilize production and build trust, making <strong>Timur Textiles</strong> a vital link between consumers seeking authenticity and artisans striving to keep their heritage alive.
      </p>

      <p style="font-size: 16px; color: #333; line-height: 1.6; margin-bottom: 10px;">
        As the global market continues to evolve amid ongoing challenges, the preservation of Oriental rug traditions remains more crucial than ever. <a href="https://www.TimurTextiles.com" target="_blank" style="color: #0073e6; text-decoration: none; font-weight: bold;">TimurTextiles.com</a> stands at the forefront of this change, ensuring that the beauty and cultural significance of these carpets endure. For anyone in search of genuine, ethically sourced Oriental rugs, <strong>Timur Textiles</strong> offers not only a product but a promise—a promise to uphold the legacy of skilled Afghan weavers while championing a future where tradition and innovation coexist harmoniously.
      </p>
    </div>
  </div>
</div>


    <!-- About Me Section -->
    <section class="about-me">
        <!-- Your photo -->
        <div style="flex: 1;">
            <img src="C:\Users\default.LAPTOP-07KBR12J\Pictures\about me.jpg" alt="Your Photo" style="width: 250px; height: 250px; border-radius: 50%; border: 5px solid white;">
        </div>
        <!-- Brief description -->
        <div style="flex: 2; margin-left: 20px;">
            <h2>About Me</h2>
            <p>AsSalamuAlaikum, I’m Ethan. My journey has been shaped by the places I’ve lived, the people I’ve met, and the lessons I’ve learned along the way.<p>

<p>In 2018, I traveled to Bali for the first time, immersing myself in local life and discovering the profound beauty of community and connection. That same year, I faced a challenging yet transformative experience when I was deported from London after a misunderstanding at the border. It was a humbling moment that taught me resilience and the importance of adaptability.<p>

<p>In 2020, I channeled my reflections and experiences into a podcast titled Open the Brain, where I explored ideas, stories, and the complexities of life. It was a creative outlet that allowed me to connect with others on a deeper level.<p>

<p>More recently, I spent a year living in Bangkok (2022-2023), just a kilometer from Khaosan Road. During that time, I became deeply connected to the community at Oh Bangkok Hostel, where I formed meaningful relationships and gained a unique perspective on local life.<p>

<p>My journey also took me to Kuala Lumpur during the same period, where I lived on and off in a hostel facing Petaling Street. In 2023, I had the opportunity to work as a background actor in The Cover Girl, an experience that gave me a glimpse into the intersection of art and culture.<p>

<p>Creativity has always been a part of my story. In high school, I published poetry on Wattpad, and over the years, I’ve continued to explore storytelling as a way to reflect on my experiences and share them with others.<p>

<p>Sadaqah has become an integral part of my life—a way to give back and honor the communities that have welcomed me. This space is a reflection of my journey, my values, and my hope to inspire others to live with purpose and compassion. Thank you for being here.”<p>
        </div>
    </section>

</body>
</html>
