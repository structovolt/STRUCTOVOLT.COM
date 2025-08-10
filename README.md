# STRUCTOVOLT.COM
body {
  margin: 0;
  font-family: Arial, sans-serif;
  line-height: 1.6;
  color: #333;
}

.hero {
  position: relative;
  height: 300px;
  background: #777;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
}

.hero-overlay {
  position: absolute;
  inset: 0;
  background: rgba(0, 0, 0, 0.4);
  z-index: 1;
}

.hero-content {
  position: relative;
  z-index: 2;
  color: #fff;
  padding: 20px;
}

.logo {
  height: 180px;
  max-width: 280px;
  object-fit: contain;
  margin: 0 auto 20px;
  display: block;
}

.hero-content h1 {
  font-size: 1.8rem;
  font-weight: bold;
  margin: 10px 0 20px 0;
}

.navbar {
  display: flex;
  justify-content: center;
  gap: 25px;
  flex-wrap: wrap;
}

.navbar a {
  color: #fff;
  text-decoration: none;
  font-weight: 600;
  font-size: 0.95rem;
  transition: color 0.3s;
}

.navbar a:hover {
  color: #ffcc00;
}

/* === Slider Section === */
#slider {
  padding: 40px 0;
  background: #f4f4f4;
  text-align: center;
}

.slider-container {
  width: 800px;
  max-width: 90%;
  margin: auto;
  border-radius: 10px;
  overflow: hidden;
  box-shadow: 0 0 12px rgba(0, 0, 0, 0.1);
  position: relative;
}

.slides {
  position: relative;
  height: 400px;
}

.slide {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 400px;
  opacity: 0;
  transition: opacity 0.2s ease-in-out;
  object-fit: cover;
  border-radius: 10px;
}

.slide.active {
  opacity: 1;
  z-index: 1;
}

.slider-btn {
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  font-size: 30px;
  color: white;
  background: rgba(0, 0, 0, 0.5);
  border: none;
  padding: 8px 14px;
  cursor: pointer;
  z-index: 2;
  border-radius: 5px;
  transition: background 0.3s;
}

.slider-btn:hover {
  background: rgba(0, 0, 0, 0.8);
}

.slider-btn.prev {
  left: 15px;
}

.slider-btn.next {
  right: 15px;
}

/* === Other Site Sections === */

section {
  padding: 60px 20px;
  max-width: 1100px;
  margin: auto;
}

h2 {
  color: #003366;
  text-align: center;
  margin-bottom: 40px;
}

.service-grid, .stats-grid {
  display: grid;
  gap: 20px;
}

.service-grid {
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
}

.stats-grid {
  grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
  text-align: center;
}

.stats-grid span {
  font-size: 2.5rem;
  color: #0055aa;
  display: block;
}

/* Footer */
footer {
  width: 100%;
  background: #002244; /* Or #001a33 / navy tone */
  color: #fff;
  text-align: center;
  padding: 20px 0;
  margin: 0;
 box-sizing: border-box;
  position: relative;
}

/* WhatsApp Floating Button */
.whatsapp-float {
  position: fixed;
  bottom: 20px;
  right: 20px;
  z-index: 100;
  height: 60px;
  width: 60px;
  cursor: pointer;
}

.whatsapp-float img {
  height: 100%;
  width: 100%;
  object-fit: cover;
  border-radius: 50%;
  box-shadow: 0 0 10px rgba(0,0,0,0.3);
  transition: transform 0.3s ease;
}

.whatsapp-float img:hover {
  transform: scale(1.1);
}

/* Project Gallery */
.project-gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
  padding-top: 20px;
}

.project-gallery img {
  width: 100%;
  height: auto;
  object-fit: contain;
  border-radius: 10px;
  box-shadow: 0 0 10px rgba(0,0,0,0.1);
  transition: transform 0.3s ease;
}

.project-gallery img:hover {
  transform: scale(1.05);
}

/* Individual Project Cards */
#projects {
  padding: 50px 20px;
  background-color: #f4f4f4;
  text-align: center;
}

.project-card {
  width: 300px;
  background: #fff;
  border-radius: 8px;
  box-shadow: 0 0 10px rgba(0,0,0,0.1);
  overflow: hidden;
  transition: transform 0.3s ease;
}

.project-card:hover {
  transform: scale(1.03);
}

.project-card img {
  width: 100%;
  height: 200px;
  object-fit: cover;
  display: block;
}

.project-card p {
  padding: 10px;
  font-size: 0.95rem;
  color: #333;
}

.menu-toggle {
  font-size: 28px;
  cursor: pointer;
  position: fixed;
  top: 20px;
  left: 20px;
  color: white;
  background: rgba(0,0,0,0.6);
  padding: 10px 15px;
  z-index: 2000;
  border-radius: 5px;
}

.sidebar {
  height: 100%;
  width: 0;
  position: fixed;
  top: 0;
  left: 0;
  background-color: #003366;
  overflow-x: hidden;
  transition: 0.3s;
  padding-top: 60px;
  z-index: 1500;
}

.sidebar a {
  padding: 12px 30px;
  text-decoration: none;
  font-size: 1.1rem;
  color: white;
  display: block;
  transition: 0.3s;
}

.sidebar a:hover {
  background-color: #004488;
}

.sidebar .closebtn {
  position: absolute;
  top: 15px;
  right: 20px;
  font-size: 28px;
  background: none;
  color: white;
  border: none;
}
.service-card {
  background: #fff;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 0 10px rgba(0,0,0,0.05);
  transition: transform 0.3s;
}

.service-card:hover {
  transform: translateY(-5px);
}

.service-card h3 {
  color: #003366;
  margin-bottom: 10px;
}

.slide {
  display: none;
}

.slide.active {
  display: block;
}

.download-btn {
  display: inline-block;
  padding: 12px 24px;
  background-color: #003366;
  color: #fff;
  text-decoration: none;
  font-weight: bold;
  border-radius: 6px;
  transition: background-color 0.3s ease;
}

.download-btn:hover {
  background-color: #0055aa;
}

/* Slider Container */
.slider-container {
  max-width: 800px;
  margin: 40px auto;
  position: relative;
  border-radius: 10px;
  overflow: hidden;
  box-shadow: 0 0 15px rgba(0,0,0,0.2);
  background: #fff;
}

/* Slides */
.slides {
  position: relative;
  height: 400px;
}

.slide {
  display: none;
  height: 100%;
  width: 100%;
  position: absolute;
  top: 0;
  left: 0;
}

.slide img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
  border-radius: 10px;
}

.slide.active {
  display: block;
}

/* Navigation Buttons */
.slider-btn {
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  background-color: rgba(0,0,0,0.5);
  color: white;
  border: none;
  font-size: 30px;
  padding: 10px 15px;
  cursor: pointer;
  border-radius: 50%;
  user-select: none;
  transition: background-color 0.3s ease;
}

.slider-btn:hover {
  background-color: rgba(0,0,0,0.8);
}

.slider-btn.prev {
  left: 15px;
}

.slider-btn.next {
  right: 15px;
}

/* Dots */
.dots {
  text-align: center;
  padding: 15px 0;
  background: #f1f1f1;
  border-radius: 0 0 10px 10px;
}

.dot {
  height: 12px;
  width: 12px;
  margin: 0 6px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

.dot.active {
  background-color: #003366;
}
/* Inquiry Form Styles */
#contact {
  max-width: 600px;
  margin: 40px auto;
  padding: 20px;
  background-color: #f9f9f9;
  border-radius: 10px;
  box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

#contact h2 {
  text-align: center;
  color: #003366;
  margin-bottom: 25px;
  font-size: 2rem;
}

#inquiryForm label {
  display: block;
  margin-bottom: 6px;
  font-weight: 600;
  color: #003366;
}

#inquiryForm input[type="text"],
#inquiryForm input[type="email"],
#inquiryForm input[type="tel"],
#inquiryForm textarea {
  width: 100%;
  padding: 12px;
  margin-bottom: 20px;
  border: 1.5px solid #ccc;
  border-radius: 6px;
  font-size: 1rem;
  transition: border-color 0.3s;
  box-sizing: border-box;
}

#inquiryForm input[type="text"]:focus,
#inquiryForm input[type="email"]:focus,
#inquiryForm input[type="tel"]:focus,
#inquiryForm textarea:focus {
  border-color: #0055aa;
  outline: none;
}

#inquiryForm textarea {
  resize: vertical;
  min-height: 120px;
}

#inquiryForm button {
  background-color: #003366;
  color: white;
  padding: 14px 28px;
  font-size: 1.1rem;
  font-weight: 700;
  border: none;
  border-radius: 6px;
  cursor: pointer;
  transition: background-color 0.3s;
  display: block;
  width: 100%;
}

#inquiryForm button:hover {
  background-color: #0055aa;
}

/* Required field asterisk */
.required {
  color: red;
  margin-left: 4px;
}

.slider-container {
  width: 100%;           /* Full width of the parent container */
  max-width: 900px;      /* Limit max width on large screens */
  margin: 0 auto;        /* Center horizontally */
  overflow: hidden;
  position: relative;
}

.slides img {
  width: 100%;           /* Full width of slider container */
  aspect-ratio: 16 / 9;  /* Keep 16:9 aspect ratio automatically */
  object-fit: cover;     /* Cover entire slide area without distortion */
  display: block;
  height: auto;          /* Let height adjust based on width */
}

/* Optional: Adjust aspect ratio for smaller screens */
@media (max-width: 600px) {
  .slides img {
    aspect-ratio: 4 / 3; /* Taller images for mobiles */
  }
}
.director {
  text-align: center;
  margin-bottom: 40px; /* spacing between directors */
}
.director img {
  height: 250px;
  width: 250px;
  border-radius: 0;
  object-fit: cover; /* keeps aspect ratio and fills circle */
}

