<!DOCTYPE html>
<html class="scroll-smooth" lang="en">
 <head>
  <meta charset="UTF-8"></meta>
  <meta content="width=device-width, initial-scale=1.0" name="viewport"></meta>
  <title>Afrin Marriage Media - #1 Trusted Matchmaking Service</title>
  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>
  
  <!-- Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&amp;family=Playfair+Display:ital,wght@0,600;0,700;1,500&amp;display=swap" rel="stylesheet"></link>
  <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+Bengali:wght@400;500;600;700&amp;display=swap" rel="stylesheet"></link>
  
  <!-- Font Awesome & Bootstrap Icons -->
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css" rel="stylesheet"></link>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.1/font/bootstrap-icons.css" rel="stylesheet"></link>
  
  <!-- AOS Animation Library -->
  <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet"></link>
  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
  
  <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            red: '#E11D48',   
                            dark: '#BE123C',
                            light: '#FFF1F2',
                            gold: '#C5A059',
                            gray: '#F9FAFB',
                            darkbg: '#111827'
                        }
                    },
                    fontFamily: {
                        sans: ['Poppins', 'sans-serif'],
                        heading: ['Playfair Display', 'serif'],
                        bengali: ['Noto Sans Bengali', 'sans-serif'],
                    }
                }
            }
        }
    </script>
  <style>
        body { 
            font-family: 'Poppins', sans-serif;
            background-color: #FAFAFA;
            color: #334155;
            overflow-x: hidden;
            line-height: 1.6;
            margin: 0;
            padding: 0;
        }
        
        html { scroll-behavior: smooth; }

        h1, h2, h3, h4, h5, h6 {
            font-family: 'Poppins', sans-serif; 
            line-height: 1.2;
        }
        .font-bengali {
            font-family: 'Noto Sans Bengali', sans-serif;
        }

        /* Custom Scrollbar */
        ::-webkit-scrollbar { width: 8px; }
        ::-webkit-scrollbar-track { background: #f1f1f1; }
        ::-webkit-scrollbar-thumb { background: #E11D48; border-radius: 4px; }
        ::-webkit-scrollbar-thumb:hover { background: #be123c; }

        /* --- BUTTON STYLES --- */
        .btn-ui {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            font-weight: 600;
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
            border-radius: 9999px;
        }
        .btn-ui:hover { transform: translateY(-2px); box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1); }
        .btn-primary { background: linear-gradient(135deg, #E11D48 0%, #BE123C 100%); color: white; }
        .btn-secondary { background: white; color: #334155; border: 2px solid #E2E8F0; }
        .btn-secondary:hover { border-color: #E11D48; color: #E11D48; }
        .btn-whatsapp { background: #25D366; color: white; }
        .btn-messenger { background: #0084FF; color: white; }

        /* --- PROFILE CARD DESIGN --- */
        .profile-card-new {
            position: relative;
            border-radius: 1.25rem;
            overflow: hidden;
            background: white;
            box-shadow: 0 4px 20px rgba(0,0,0,0.06);
            transition: all 0.4s ease;
            height: 100%;
            border: 1px solid rgba(0,0,0,0.04);
        }
        .profile-card-new:hover {
            transform: translateY(-8px);
            box-shadow: 0 20px 40px rgba(225, 29, 72, 0.15);
            border-color: rgba(225, 29, 72, 0.2);
        }
        .profile-img-new { height: 240px; overflow: hidden; position: relative; }
        .profile-img-new img { width: 100%; height: 100%; object-fit: cover; transition: transform 0.6s ease; }
        .profile-card-new:hover .profile-img-new img { transform: scale(1.08); }
        .profile-img-new::after {
            content: ''; position: absolute; bottom: 0; left: 0; width: 100%; height: 50%;
            background: linear-gradient(to top, rgba(0,0,0,0.6), transparent); z-index: 1;
        }
        .profile-badges-new { position: absolute; top: 12px; left: 12px; display: flex; gap: 6px; z-index: 2; }
        .badge-new {
            background: rgba(255, 255, 255, 0.95); backdrop-filter: blur(4px); padding: 4px 10px;
            border-radius: 20px; font-size: 0.7rem; font-weight: 700; color: #333;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1); display: flex; align-items: center; gap: 4px;
        }
        .badge-new.verified { background: #E11D48; color: white; }
        .profile-info-overlay {
            position: absolute; bottom: 0; left: 0; width: 100%; padding: 12px 16px; z-index: 2;
            display: flex; justify-content: space-between; align-items: flex-end;
        }
        .profile-name-new { color: white; font-weight: 700; font-size: 1.1rem; text-shadow: 0 1px 4px rgba(0,0,0,0.3); }
        .profile-id-new { color: rgba(255,255,255,0.9); font-size: 0.75rem; font-weight: 500; }
        .profile-age-badge { background: white; color: #E11D48; font-size: 0.8rem; font-weight: 700; padding: 4px 10px; border-radius: 20px; box-shadow: 0 2px 5px rgba(0,0,0,0.1); }
        .profile-body-new { padding: 1rem 1.25rem 1.25rem; }
        .profile-details-row { display: flex; flex-wrap: wrap; gap: 8px; margin-bottom: 1rem; }
        .detail-tag { background: #F8FAFC; color: #64748b; font-size: 0.75rem; font-weight: 500; padding: 4px 10px; border-radius: 6px; border: 1px solid #F1F5F9; display: flex; align-items: center; gap: 4px; }
        .detail-tag i { color: #CBD5E1; font-size: 0.7rem; }

        /* --- SUCCESS STORIES --- */
        .news-card { background: white; border-radius: 1rem; overflow: hidden; border: 1px solid #e5e7eb; transition: all 0.3s ease; display: flex; flex-direction: column; height: 100%; }
        .news-card:hover { transform: translateY(-5px); box-shadow: 0 20px 40px -5px rgba(0,0,0,0.1); border-color: #E11D48; }
        .news-img-wrapper { position: relative; height: 220px; overflow: hidden; }
        .news-img-wrapper img { width: 100%; height: 100%; object-fit: cover; transition: transform 0.5s ease; }
        .news-card:hover .news-img-wrapper img { transform: scale(1.05); }
        .news-category { position: absolute; top: 15px; left: 15px; background: #E11D48; color: white; padding: 0.25rem 0.75rem; border-radius: 4px; font-size: 0.7rem; font-weight: 700; text-transform: uppercase; }
        .news-content { padding: 1.5rem; display: flex; flex-direction: column; flex-grow: 1; }
        .news-meta { display: flex; align-items: center; gap: 1rem; margin-bottom: 0.75rem; font-size: 0.75rem; color: #64748b; }
        .news-title { font-size: 1.1rem; font-weight: 700; color: #1e293b; margin-bottom: 0.5rem; line-height: 1.4; transition: color 0.3s; }
        .news-card:hover .news-title { color: #E11D48; }
        .news-excerpt { font-size: 0.9rem; color: #64748b; line-height: 1.6; margin-bottom: 1rem; flex-grow: 1; }
        .news-link { margin-top: auto; font-size: 0.85rem; font-weight: 600; color: #E11D48; display: flex; align-items: center; gap: 0.5rem; }

        /* =========================================
           HERO SLIDER CSS (Fixed Alignment)
           ========================================= */
        .hero-slider {
            position: relative;
            width: 100%;
            height: 85vh;
            min-height: 600px;
            overflow: hidden;
        }
        .slide {
            position: absolute; top: 0; left: 0; width: 100%; height: 100%;
            opacity: 0; visibility: hidden; transition: opacity 1s ease-in-out, visibility 1s; z-index: 1;
        }
        .slide.active { opacity: 1; visibility: visible; z-index: 2; }
        .slide-bg {
            position: absolute; top: 0; left: 0; width: 100%; height: 100%;
            background-size: cover; background-position: center;
            transform: scale(1.1); transition: transform 6s linear;
        }
        .slide.active .slide-bg { transform: scale(1); }
        .slide-overlay {
            position: absolute; top: 0; left: 0; width: 100%; height: 100%;
            background: linear-gradient(to right, rgba(255,255,255,0.95) 0%, rgba(255,255,255,0.85) 40%, rgba(255,255,255,0.4) 70%, rgba(0,0,0,0.2) 100%);
        }
        .slide-content {
            opacity: 0; transform: translateY(30px); transition: all 0.8s ease-out; transition-delay: 0.3s;
        }
        .slide.active .slide-content { opacity: 1; transform: translateY(0); }

        /* Slider Controls */
        .slider-control {
            position: absolute; top: 50%; transform: translateY(-50%); width: 50px; height: 50px;
            background: rgba(255, 255, 255, 0.2); backdrop-filter: blur(5px); border: 1px solid rgba(255,255,255,0.5);
            border-radius: 50%; display: flex; align-items: center; justify-content: center;
            color: #333; font-size: 1.2rem; cursor: pointer; z-index: 10; transition: all 0.3s ease;
        }
        .slider-control:hover { background: white; color: #E11D48; }
        .prev-btn { left: 2%; } .next-btn { right: 2%; }
        .slider-dots { position: absolute; bottom: 30px; left: 50%; transform: translateX(-50%); display: flex; gap: 12px; z-index: 10; }
        .dot { width: 12px; height: 12px; border-radius: 50%; background: rgba(255, 255, 255, 0.5); border: 1px solid #E11D48; cursor: pointer; transition: all 0.3s ease; }
        .dot.active { background: #E11D48; transform: scale(1.2); }

        /* =========================================
           WHY CHOOSE US SECTION CSS
           ========================================= */
        .features-section { padding: 6rem 5%; max-width: 1300px; margin: 0 auto; }
        .section-header { text-align: center; margin-bottom: 4rem; width: 100%; }
        .section-header h2 { font-size: 2.8rem; font-weight: 700; margin-bottom: 1rem; background: linear-gradient(135deg, #E11D48, #F43F5E); -webkit-background-clip: text; color: transparent; }
        .section-header p { color: #64748b; font-size: 1.1rem; max-width: 600px; margin: 0 auto; }
        .features-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 2.5rem; width: 100%; }
        .feature-card { background: white; padding: 3rem 2rem; border-radius: 1.5rem; text-align: center; border: 1px solid rgba(0,0,0,0.05); box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.05); transition: all 0.3s; opacity: 0; transform: translateY(30px); }
        .feature-card.visible { opacity: 1; transform: translateY(0); }
        .feature-card:hover { transform: translateY(-12px); box-shadow: 0 20px 40px -5px rgba(225, 29, 72, 0.1); }
        .icon-box { width: 80px; height: 80px; margin: 0 auto 2rem; display: flex; align-items: center; justify-content: center; border-radius: 50%; font-size: 2.5rem; transition: all 0.3s; }
        .feature-card:nth-child(odd) .icon-box { background: rgba(225, 29, 72, 0.08); color: #E11D48; }
        .feature-card:nth-child(even) .icon-box { background: rgba(244, 63, 94, 0.08); color: #F43F5E; }
        .feature-card:hover .icon-box { transform: scale(1.1) rotate(-5deg); background: linear-gradient(135deg, #E11D48, #F43F5E); color: white; box-shadow: 0 10px 20px rgba(225, 29, 72, 0.3); }
        .feature-card h5 { font-size: 1.35rem; font-weight: 600; margin-bottom: 1rem; color: #334155; }
        .feature-card p { color: #64748b; font-size: 1rem; line-height: 1.8; }
    </style>
 </head>
 <body class="antialiased selection:bg-brand-red selection:text-white">

  <!-- HERO SLIDER SECTION (Fixed Top Alignment) -->
  <section class="relative bg-gray-50">
      <div class="hero-slider" id="heroSlider">
          
          <!-- Slide 1 -->
          <div class="slide active">
              <div class="slide-bg" style="background-image: url('https://images.unsplash.com/photo-1519741497674-611481863552?q=80&w=2070&auto=format&fit=crop');"></div>
              <div class="slide-overlay"></div>
              <!-- Changed items-center to items-start and added pt-20 -->
              <div class="absolute inset-0 flex items-start pt-20 md:pt-24">
                  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 w-full grid grid-cols-1 md:grid-cols-2 gap-12 items-center">
                      <!-- Removed pt-10 from slide-content to reduce gap -->
                      <div class="slide-content max-w-2xl">
                          <span class="inline-block py-1 px-3 rounded-full bg-white/80 border border-brand-gold text-brand-red text-xs font-bold mb-4 shadow-sm">
                              <i class="fas fa-star text-brand-gold mr-1"></i> Bangladesh's Trusted Matrimony
                          </span>
                          <h2 class="text-4xl md:text-5xl lg:text-6xl font-bold text-gray-900 leading-tight mb-5 font-heading">
                              আপনার ছেলে-মেয়ে অথবা <br/><span class="text-brand-red">নিজের জন্য</span> পছন্দের পাত্র-পাত্রী খুঁজে নিন
                          </h2>
                          <p class="text-lg text-gray-700 mb-6 font-bengali leading-relaxed">
                              এখান থেকেই। আমাদের কাছে রয়েছে অবিবাহিত, ডিভোর্স, বিধবা ও বিপত্নীকসহ অসংখ্য ক্যাটাগরির যাচাইকৃত প্রোফাইল।
                          </p>
                          <div class="flex flex-col sm:flex-row gap-3">
                              <a href="#profiles" class="btn-ui btn-primary px-8 py-3.5 text-white shadow-lg">Find Matches</a>
                              <a href="https://wa.me/8801805412128" class="btn-ui btn-whatsapp px-8 py-3.5 shadow-lg"><i class="fab fa-whatsapp mr-2"></i> Consult Now</a>
                          </div>
                      </div>
                  </div>
              </div>
          </div>

          <!-- Slide 2 -->
          <div class="slide">
              <div class="slide-bg" style="background-image: url('https://images.unsplash.com/photo-1573496359142-b8d87734a5a2?q=80&w=1974&auto=format&fit=crop');"></div>
              <div class="slide-overlay"></div>
              <div class="absolute inset-0 flex items-start pt-20 md:pt-24">
                  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 w-full grid grid-cols-1 md:grid-cols-2 gap-12 items-center">
                      <div class="slide-content max-w-2xl">
                          <span class="inline-block py-1 px-3 rounded-full bg-white/80 border border-brand-gold text-brand-red text-xs font-bold mb-4 shadow-sm">
                              Smart & Secure
                          </span>
                          <h2 class="text-4xl md:text-5xl lg:text-6xl font-bold text-gray-900 leading-tight mb-5 font-heading">
                              নিশ্চিন্তে পাত্র-পাত্রী খুঁজুন
                          </h2>
                          <p class="text-lg text-gray-700 mb-6 font-bengali leading-relaxed">
                              শিক্ষা ও পেশাগত যোগ্যতা অনুযায়ী সঠিক জীবনসঙ্গী খুঁজে নিতে আজই প্রোফাইল তৈরি করুন।
                          </p>
                          <div class="flex flex-col sm:flex-row gap-3">
                              <a href="https://forms.gle/U17sPuPLFYrznFoQ9" class="btn-ui btn-primary px-8 py-3.5 text-white shadow-lg">Register Free</a>
                              <a href="#packages" class="btn-ui btn-secondary px-8 py-3.5 text-gray-700">View Plans</a>
                          </div>
                      </div>
                  </div>
              </div>
          </div>

          <!-- Slider Controls -->
          <button class="slider-control prev-btn hidden md:flex" id="prevBtn"><i class="fas fa-chevron-left"></i></button>
          <button class="slider-control next-btn hidden md:flex" id="nextBtn"><i class="fas fa-chevron-right"></i></button>
          <div class="slider-dots" id="sliderDots"></div>
      </div>
  </section>

  <!-- Phone CTA -->
  <section class="py-16 bg-brand-red relative overflow-hidden">
   <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
    <div class="flex flex-col md:flex-row items-center justify-between gap-12 bg-white rounded-3xl p-8 md:p-12 shadow-2xl">
     <div class="text-center md:text-left md:w-1/2" data-aos="fade-right">
      <h2 class="text-3xl font-bold text-gray-900 mb-3">Need Immediate Assistance?</h2>
      <p class="text-gray-600">Our marriage experts are ready to help you find your perfect match instantly.</p>
     </div>
     <div class="flex flex-col sm:flex-row gap-4 w-full md:w-auto" data-aos="fade-left">
       <a class="flex items-center justify-center gap-3 px-8 py-4 bg-gray-50 hover:bg-gray-100 rounded-xl font-bold text-gray-800 transition border border-gray-200 group" href="tel:+8809617179128"> 
         <span class="bg-brand-red text-white p-2 rounded-lg group-hover:scale-110 transition"><i class="fas fa-phone-alt"></i></span>
         +880 9617 179 128 
       </a> 
       <a class="flex items-center justify-center gap-3 px-8 py-4 bg-[#25D366] hover:bg-[#20BD5A] text-white rounded-xl font-bold shadow-lg shadow-green-200 transition" href="https://wa.me/8801805412128"> 
         <i class="fab fa-whatsapp text-2xl"></i> Chat Now 
       </a>
     </div>
    </div>
   </div>
  </section>

  <!-- Featured Biodatas (8 Cards) -->
  <section class="py-20 bg-white" id="profiles">
   <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="text-center mb-12" data-aos="fade-up">
     <span class="text-brand-red font-bold tracking-widest uppercase text-xs mb-3 block">New Members</span>
     <h2 class="text-4xl font-extrabold text-gray-900 section-title mb-4">Featured Biodatas</h2>
     <div class="w-20 h-1 bg-brand-red mx-auto rounded-full"></div>
    </div>
    
    <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">
     
     <!-- Profile 1 -->
     <div class="profile-card-new" data-aos="fade-up">
      <div class="profile-img-new">
       <img alt="Washim" src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjjaKh4J8MhKE78AeuXHlgvAETpqSwRsuf0TpqSXcg5exXDpE2afppYxmI6Znyp8qdyKsPDll6Hvl5rv9B6UZKPwz-H2jVFG0_tzN51s8gAYgQ3b_GQtY8k-Pruml8u0ckSnJecBXPVp7oKMTjUaQkqlAPg3xFeQsFI4OJOS83ohijjzSeGeRcyNiKWgog/s1600/1000161812.jpg" />
       <div class="profile-badges-new"><div class="badge-new verified"><i class="fas fa-check-circle"></i> Verified</div></div>
       <div class="profile-info-overlay">
         <div><div class="profile-name-new">Washim Khan</div><div class="profile-id-new">ID: AMM-1025</div></div>
         <div class="profile-age-badge">44 Yrs</div>
       </div>
      </div>
      <div class="profile-body-new">
       <div class="profile-details-row">
         <span class="detail-tag"><i class="fas fa-briefcase"></i> Hotel Mgmt</span>
         <span class="detail-tag"><i class="fas fa-map-marker-alt"></i> Dhaka</span>
         <span class="detail-tag"><i class="fas fa-ruler-vertical"></i> 5' 8"</span>
       </div>
       <div class="flex gap-2">
        <a class="btn-ui btn-whatsapp flex-1 py-2 text-xs font-bold rounded-lg" href="https://wa.me/8801805412128?text=I want to view full CV of ID: AMM-1025" target="_blank"><i class="fab fa-whatsapp mr-1"></i> WhatsApp</a> 
        <a class="btn-ui btn-messenger flex-1 py-2 text-xs font-bold rounded-lg" href="https://m.me/afrinmarriage?text=I want to view full CV of ID: AMM-1025" target="_blank"><i class="fab fa-facebook-messenger mr-1"></i> Chat</a>
       </div>
      </div>
     </div>

     <!-- Profile 2 -->
     <div class="profile-card-new" data-aos="fade-up" data-aos-delay="50">
      <div class="profile-img-new">
       <img alt="Mim Islam" src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEiDpx4NjnLQV2ZKjtaKiNn5o6NRy1yhP1YrA4ilIo5kZ8RQkbR301aGsexp7NkJtgvS-lTmaKFp7a4WH4GkybIygm0GlrgpV5KHaMSrWDuD2Omc-gjIQV-xL6Gv3zrGsGiuHWArSQeHlYO5zL1uxBxhdUtQptAuM8WZZQk2vq8xzF1RRv2KBr-wnUdFi0k/s1600/1000161814.jpg" />
       <div class="profile-badges-new"><div class="badge-new verified"><i class="fas fa-check-circle"></i> Verified</div></div>
       <div class="profile-info-overlay">
         <div><div class="profile-name-new">Mim Islam</div><div class="profile-id-new">ID: AMM-1042</div></div>
         <div class="profile-age-badge">29 Yrs</div>
       </div>
      </div>
      <div class="profile-body-new">
       <div class="profile-details-row">
         <span class="detail-tag"><i class="fas fa-briefcase"></i> Banker</span>
         <span class="detail-tag"><i class="fas fa-map-marker-alt"></i> Chittagong</span>
         <span class="detail-tag"><i class="fas fa-ruler-vertical"></i> 5' 3"</span>
       </div>
       <div class="flex gap-2">
        <a class="btn-ui btn-whatsapp flex-1 py-2 text-xs font-bold rounded-lg" href="https://wa.me/8801805412128?text=I want to view full CV of ID: AMM-1042" target="_blank"><i class="fab fa-whatsapp mr-1"></i> WhatsApp</a> 
        <a class="btn-ui btn-messenger flex-1 py-2 text-xs font-bold rounded-lg" href="https://m.me/afrinmarriage?text=I want to view full CV of ID: AMM-1042" target="_blank"><i class="fab fa-facebook-messenger mr-1"></i> Chat</a>
       </div>
      </div>
     </div>

     <!-- Profile 3 -->
     <div class="profile-card-new" data-aos="fade-up" data-aos-delay="100">
      <div class="profile-img-new">
       <img alt="Nusrat" src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhFZzygiOkX6lOJLqHkLsUhU0LEHV1nlaCp60EMh1cjQLfuHUtmwscVs79tc6sEyj1Ld6YofLG2isF6Tjxwvg6GqSLgunXgizygXQsU_TTOBOIUoEqrw8IbGOTBD3oIEuSdjJmL3bDKREtzjPt2MVbVD7_HFbcGVTkFnlSRGDjDW-hpKKUR1EVFUkHibXQ/s1600/1000161807.png" />
       <div class="profile-badges-new"><div class="badge-new verified"><i class="fas fa-check-circle"></i> Verified</div></div>
       <div class="profile-info-overlay">
         <div><div class="profile-name-new">Ms. Nusrat</div><div class="profile-id-new">ID: AMM-2105</div></div>
         <div class="profile-age-badge">23 Yrs</div>
       </div>
      </div>
      <div class="profile-body-new">
       <div class="profile-details-row">
         <span class="detail-tag"><i class="fas fa-graduation-cap"></i> M.Sc Student</span>
         <span class="detail-tag"><i class="fas fa-map-marker-alt"></i> Sylhet</span>
         <span class="detail-tag"><i class="fas fa-ruler-vertical"></i> 5' 4"</span>
       </div>
       <div class="flex gap-2">
        <a class="btn-ui btn-whatsapp flex-1 py-2 text-xs font-bold rounded-lg" href="https://wa.me/8801805412128?text=I want to view full CV of ID: AMM-2105" target="_blank"><i class="fab fa-whatsapp mr-1"></i> WhatsApp</a> 
        <a class="btn-ui btn-messenger flex-1 py-2 text-xs font-bold rounded-lg" href="https://m.me/afrinmarriage?text=I want to view full CV of ID: AMM-2105" target="_blank"><i class="fab fa-facebook-messenger mr-1"></i> Chat</a>
       </div>
      </div>
     </div>

     <!-- Profile 4 -->
     <div class="profile-card-new" data-aos="fade-up" data-aos-delay="150">
      <div class="profile-img-new">
       <img alt="Shakir" src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhjae5QJA-KiEOKvZPHbaGZ8l_iR8ljOwONV2_B4FLAiM706XZWbQoqGqrRoRefoqOIC510lVJTRI8xPcYDSR4jjF1wWJZ-XB-FzXjQPCGB7vv3iMqjwbMvZrR3BaJjCeOEwjx5V4Hcxttrn125tNadKiDlYnKGywgOU0R1X3PGoJnp5NwA4C9KddjnCdg/s1600/1000161817.jpg" />
       <div class="profile-badges-new"><div class="badge-new verified"><i class="fas fa-check-circle"></i> Verified</div></div>
       <div class="profile-info-overlay">
         <div><div class="profile-name-new">Shakir Ahmed</div><div class="profile-id-new">ID: AMM-2250</div></div>
         <div class="profile-age-badge">30 Yrs</div>
       </div>
      </div>
      <div class="profile-body-new">
       <div class="profile-details-row">
         <span class="detail-tag"><i class="fas fa-briefcase"></i> Engineer</span>
         <span class="detail-tag"><i class="fas fa-map-marker-alt"></i> Dhaka</span>
         <span class="detail-tag"><i class="fas fa-ruler-vertical"></i> 5' 9"</span>
       </div>
       <div class="flex gap-2">
        <a class="btn-ui btn-whatsapp flex-1 py-2 text-xs font-bold rounded-lg" href="https://wa.me/8801805412128?text=I want to view full CV of ID: AMM-2250" target="_blank"><i class="fab fa-whatsapp mr-1"></i> WhatsApp</a> 
        <a class="btn-ui btn-messenger flex-1 py-2 text-xs font-bold rounded-lg" href="https://m.me/afrinmarriage?text=I want to view full CV of ID: AMM-2250" target="_blank"><i class="fab fa-facebook-messenger mr-1"></i> Chat</a>
       </div>
      </div>
     </div>

     <!-- Profile 5 -->
     <div class="profile-card-new" data-aos="fade-up">
      <div class="profile-img-new">
       <img alt="Farzana" src="https://images.unsplash.com/photo-1544005313-94ddf0286df2?q=80&w=1976&auto=format&fit=crop" />
       <div class="profile-badges-new"><div class="badge-new verified"><i class="fas fa-check-circle"></i> Verified</div></div>
       <div class="profile-info-overlay">
         <div><div class="profile-name-new">Farzana Akter</div><div class="profile-id-new">ID: AMM-3301</div></div>
         <div class="profile-age-badge">25 Yrs</div>
       </div>
      </div>
      <div class="profile-body-new">
       <div class="profile-details-row">
         <span class="detail-tag"><i class="fas fa-briefcase"></i> Teacher</span>
         <span class="detail-tag"><i class="fas fa-map-marker-alt"></i> Rajshahi</span>
         <span class="detail-tag"><i class="fas fa-ruler-vertical"></i> 5' 2"</span>
       </div>
       <div class="flex gap-2">
        <a class="btn-ui btn-whatsapp flex-1 py-2 text-xs font-bold rounded-lg" href="https://wa.me/8801805412128?text=I want to view full CV of ID: AMM-3301" target="_blank"><i class="fab fa-whatsapp mr-1"></i> WhatsApp</a> 
        <a class="btn-ui btn-messenger flex-1 py-2 text-xs font-bold rounded-lg" href="https://m.me/afrinmarriage?text=I want to view full CV of ID: AMM-3301" target="_blank"><i class="fab fa-facebook-messenger mr-1"></i> Chat</a>
       </div>
      </div>
     </div>

     <!-- Profile 6 -->
     <div class="profile-card-new" data-aos="fade-up" data-aos-delay="50">
      <div class="profile-img-new">
       <img alt="Rifat" src="https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?q=80&w=1974&auto=format&fit=crop" />
       <div class="profile-badges-new"><div class="badge-new verified"><i class="fas fa-check-circle"></i> Verified</div></div>
       <div class="profile-info-overlay">
         <div><div class="profile-name-new">Rifat Hossain</div><div class="profile-id-new">ID: AMM-3305</div></div>
         <div class="profile-age-badge">32 Yrs</div>
       </div>
      </div>
      <div class="profile-body-new">
       <div class="profile-details-row">
         <span class="detail-tag"><i class="fas fa-briefcase"></i> Businessman</span>
         <span class="detail-tag"><i class="fas fa-map-marker-alt"></i> Khulna</span>
         <span class="detail-tag"><i class="fas fa-ruler-vertical"></i> 5' 10"</span>
       </div>
       <div class="flex gap-2">
        <a class="btn-ui btn-whatsapp flex-1 py-2 text-xs font-bold rounded-lg" href="https://wa.me/8801805412128?text=I want to view full CV of ID: AMM-3305" target="_blank"><i class="fab fa-whatsapp mr-1"></i> WhatsApp</a> 
        <a class="btn-ui btn-messenger flex-1 py-2 text-xs font-bold rounded-lg" href="https://m.me/afrinmarriage?text=I want to view full CV of ID: AMM-3305" target="_blank"><i class="fab fa-facebook-messenger mr-1"></i> Chat</a>
       </div>
      </div>
     </div>

     <!-- Profile 7 -->
     <div class="profile-card-new" data-aos="fade-up" data-aos-delay="100">
      <div class="profile-img-new">
       <img alt="Tasnim" src="https://images.unsplash.com/photo-1573497019940-1c28c88b4f3e?q=80&w=1887&auto=format&fit=crop" />
       <div class="profile-badges-new"><div class="badge-new verified"><i class="fas fa-check-circle"></i> Verified</div></div>
       <div class="profile-info-overlay">
         <div><div class="profile-name-new">Tasnim Rahman</div><div class="profile-id-new">ID: AMM-3310</div></div>
         <div class="profile-age-badge">27 Yrs</div>
       </div>
      </div>
      <div class="profile-body-new">
       <div class="profile-details-row">
         <span class="detail-tag"><i class="fas fa-briefcase"></i> Doctor</span>
         <span class="detail-tag"><i class="fas fa-map-marker-alt"></i> Dhaka</span>
         <span class="detail-tag"><i class="fas fa-ruler-vertical"></i> 5' 5"</span>
       </div>
       <div class="flex gap-2">
        <a class="btn-ui btn-whatsapp flex-1 py-2 text-xs font-bold rounded-lg" href="https://wa.me/8801805412128?text=I want to view full CV of ID: AMM-3310" target="_blank"><i class="fab fa-whatsapp mr-1"></i> WhatsApp</a> 
        <a class="btn-ui btn-messenger flex-1 py-2 text-xs font-bold rounded-lg" href="https://m.me/afrinmarriage?text=I want to view full CV of ID: AMM-3310" target="_blank"><i class="fab fa-facebook-messenger mr-1"></i> Chat</a>
       </div>
      </div>
     </div>

     <!-- Profile 8 -->
     <div class="profile-card-new" data-aos="fade-up" data-aos-delay="150">
      <div class="profile-img-new">
       <img alt="Sadia" src="https://images.unsplash.com/photo-1534528741775-53994a69daeb?q=80&w=1976&auto=format&fit=crop" />
       <div class="profile-badges-new"><div class="badge-new verified"><i class="fas fa-check-circle"></i> Verified</div></div>
       <div class="profile-info-overlay">
         <div><div class="profile-name-new">Sadia Karim</div><div class="profile-id-new">ID: AMM-3315</div></div>
         <div class="profile-age-badge">24 Yrs</div>
       </div>
      </div>
      <div class="profile-body-new">
       <div class="profile-details-row">
         <span class="detail-tag"><i class="fas fa-briefcase"></i> Engineer</span>
         <span class="detail-tag"><i class="fas fa-map-marker-alt"></i> Sylhet</span>
         <span class="detail-tag"><i class="fas fa-ruler-vertical"></i> 5' 4"</span>
       </div>
       <div class="flex gap-2">
        <a class="btn-ui btn-whatsapp flex-1 py-2 text-xs font-bold rounded-lg" href="https://wa.me/8801805412128?text=I want to view full CV of ID: AMM-3315" target="_blank"><i class="fab fa-whatsapp mr-1"></i> WhatsApp</a> 
        <a class="btn-ui btn-messenger flex-1 py-2 text-xs font-bold rounded-lg" href="https://m.me/afrinmarriage?text=I want to view full CV of ID: AMM-3315" target="_blank"><i class="fab fa-facebook-messenger mr-1"></i> Chat</a>
       </div>
      </div>
     </div>

    </div>
   </div>
  </section>

  <!-- Why Choose Us -->
  <section class="features-section bg-gray-50" id="why-choose">
      <div class="section-header">
          <h2>Why Choose Us</h2>
          <p>We provide a trusted platform with advanced technology to help you find your perfect life partner.</p>
      </div>
      <div class="features-grid">
          <div class="feature-card"><div class="icon-box"><i class="bi bi-shield-check"></i></div><h5>Verified Profiles</h5><p>We ensure authenticity by verifying every profile.</p></div>
          <div class="feature-card"><div class="icon-box"><i class="bi bi-search"></i></div><h5>Smart Search</h5><p>Our advanced search filters allow you to find matches based on criteria.</p></div>
          <div class="feature-card"><div class="icon-box"><i class="bi bi-lock-fill"></i></div><h5>Privacy Protected</h5><p>Your personal information is secure with us.</p></div>
          <div class="feature-card"><div class="icon-box"><i class="bi bi-headset"></i></div><h5>24/7 Support</h5><p>Our dedicated team is available around the clock.</p></div>
          <div class="feature-card"><div class="icon-box"><i class="bi bi-file-person"></i></div><h5>Detailed Profiles</h5><p>Access comprehensive biodata to make decisions.</p></div>
          <div class="feature-card"><div class="icon-box"><i class="bi bi-lightning-charge-fill"></i></div><h5>Quick Matching</h5><p>Get instant match suggestions through our algorithm.</p></div>
      </div>
  </section>

  <!-- PACKAGE SECTION (Self Service & Premium Highlighted) -->
  <section class="py-20 bg-white" id="packages">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="text-center mb-12" data-aos="fade-up">
        <span class="text-brand-red font-bold tracking-widest uppercase text-xs mb-3 block">Membership Plans</span>
        <h2 class="text-4xl font-extrabold text-gray-900 mt-2 mb-4">Choose Your Plan</h2>
      </div>
      
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
        
        <!-- Plan 1: Self Service -->
        <div class="bg-gray-50 border border-gray-200 rounded-2xl p-8 flex flex-col hover:shadow-md transition duration-300" data-aos="fade-up">
          <div class="mb-6"><h3 class="text-xl font-bold text-gray-900">সেলফ সার্ভিস</h3><p class="text-sm text-gray-500 mt-1">Manage your own profile</p></div>
          <div class="mb-6"><span class="text-4xl font-bold text-gray-900">৳৪,৫০০</span><span class="text-sm text-gray-500 ml-1">/ 3 মাস</span></div>
          <ul class="space-y-3 text-sm text-gray-600 mb-8 flex-grow">
            <li class="flex items-center gap-2"><i class="fas fa-check text-brand-red"></i> ভেরিফাইড বায়োডাটা লিস্টিং</li>
            <li class="flex items-center gap-2"><i class="fas fa-check text-brand-red"></i> ১০টি কোয়ালিফাইড ম্যাচ</li>
            <li class="flex items-center gap-2"><i class="fas fa-check text-brand-red"></i> সরাসরি যোগাযোগ</li>
            <li class="flex items-center gap-2"><i class="fas fa-check text-brand-red"></i> প্রাইভেসি কন্ট্রোল</li>
          </ul>
          <a href="https://wa.me/8801805412128?text=Hi!%20I%20want%20Self%20Service%20Plan" class="block text-center bg-white border border-gray-300 text-gray-800 font-semibold py-3 rounded-full hover:bg-gray-100 transition">Choose Plan</a>
        </div>

        <!-- Plan 2: Basic -->
        <div class="bg-gray-50 border border-gray-200 rounded-2xl p-8 flex flex-col hover:shadow-md transition duration-300" data-aos="fade-up" data-aos-delay="50">
          <div class="mb-6"><h3 class="text-xl font-bold text-gray-900">বেসিক প্যাকেজ</h3><p class="text-sm text-gray-500 mt-1">Start your journey</p></div>
          <div class="mb-6"><span class="text-4xl font-bold text-gray-900">৳৭,৫০০</span><span class="text-sm text-gray-500 ml-1">/ 3 মাস</span></div>
          <ul class="space-y-3 text-sm text-gray-600 mb-8 flex-grow">
            <li class="flex items-center gap-2"><i class="fas fa-check text-brand-red"></i> ফিচার্ড প্রোফাইল লিস্টিং</li>
            <li class="flex items-center gap-2"><i class="fas fa-check text-brand-red"></i> ১৫টি প্রিমিয়াম ম্যাচ</li>
            <li class="flex items-center gap-2"><i class="fas fa-check text-brand-red"></i> সিকিউর ভিডিও কলিং</li>
          </ul>
          <a href="https://wa.me/8801805412128?text=Hi!%20I%20want%20Basic%20Plan" class="block text-center bg-white border border-gray-300 text-gray-800 font-semibold py-3 rounded-full hover:bg-gray-100 transition">Choose Plan</a>
        </div>

        <!-- Plan 3: Premium (Highlighted) -->
        <div class="bg-white border-2 border-brand-red rounded-2xl p-8 flex flex-col relative shadow-lg" data-aos="fade-up" data-aos-delay="100">
          <span class="absolute -top-3 left-1/2 -translate-x-1/2 bg-brand-red text-white text-xs font-bold px-4 py-1 rounded-full shadow">RECOMMENDED</span>
          <div class="mb-6"><h3 class="text-xl font-bold text-gray-900">প্রিমিয়াম প্যাকেজ</h3><p class="text-sm text-gray-500 mt-1">Best value for serious seekers</p></div>
          <div class="mb-6"><span class="text-4xl font-bold text-brand-red">৳১১,৫০০</span><span class="text-sm text-gray-500 ml-1">/ 6 মাস</span></div>
          <ul class="space-y-3 text-sm text-gray-600 mb-8 flex-grow">
            <li class="flex items-center gap-2"><i class="fas fa-check text-brand-red"></i> ডেডিকেটেড অফিসার (DRO)</li>
            <li class="flex items-center gap-2"><i class="fas fa-check text-brand-red"></i> প্রায়োরিটি ম্যাচিং</li>
            <li class="flex items-center gap-2"><i class="fas fa-check text-brand-red"></i> ভিআইপি ব্যাজ</li>
            <li class="flex items-center gap-2"><i class="fas fa-check text-brand-red"></i> ক্রস-প্ল্যাটফর্ম প্রমোশন</li>
          </ul>
          <a href="https://wa.me/8801805412128?text=Hi!%20I%20want%20Premium%20Plan" class="block text-center bg-brand-red text-white font-semibold py-3 rounded-full hover:bg-brand-dark transition shadow-md">Choose Plan</a>
        </div>

        <!-- Plan 4: Golden -->
        <div class="bg-gray-50 border border-gray-200 rounded-2xl p-8 flex flex-col hover:shadow-md transition duration-300" data-aos="fade-up" data-aos-delay="150">
          <div class="mb-6"><h3 class="text-xl font-bold text-gray-900">গোল্ডেন প্যাকেজ</h3><p class="text-sm text-gray-500 mt-1">Long-term value</p></div>
          <div class="mb-6"><span class="text-4xl font-bold text-gray-900">৳১৪,৫০০</span><span class="text-sm text-gray-500 ml-1">/ 1 বছর</span></div>
          <ul class="space-y-3 text-sm text-gray-600 mb-8 flex-grow">
            <li class="flex items-center gap-2"><i class="fas fa-check text-brand-red"></i> প্রিমিয়াম ভেরিফাইড অ্যাক্সেস</li>
            <li class="flex items-center gap-2"><i class="fas fa-check text-brand-red"></i> আনলিমিটেড যোগাযোগ</li>
          </ul>
          <a href="https://wa.me/8801805412128?text=Hi!%20I%20want%20Golden%20Plan" class="block text-center bg-white border border-gray-300 text-gray-800 font-semibold py-3 rounded-full hover:bg-gray-100 transition">Choose Plan</a>
        </div>

        <!-- Plan 5: Diamond -->
        <div class="bg-gray-50 border border-gray-200 rounded-2xl p-8 flex flex-col hover:shadow-md transition duration-300" data-aos="fade-up" data-aos-delay="200">
          <div class="mb-6"><h3 class="text-xl font-bold text-gray-900">ডায়মন্ড প্যাকেজ</h3><p class="text-sm text-gray-500 mt-1">Exclusive service</p></div>
          <div class="mb-6"><span class="text-4xl font-bold text-gray-900">৳১৭,০০০</span><span class="text-sm text-gray-500 ml-1">/ 1 বছর</span></div>
          <ul class="space-y-3 text-sm text-gray-600 mb-8 flex-grow">
            <li class="flex items-center gap-2"><i class="fas fa-check text-brand-red"></i> ব্যক্তিগত ম্যানেজার</li>
            <li class="flex items-center gap-2"><i class="fas fa-check text-brand-red"></i> ভিআইপি ডাটাবেস অ্যাক্সেস</li>
          </ul>
          <a href="https://wa.me/8801805412128?text=Hi!%20I%20want%20Diamond%20Plan" class="block text-center bg-white border border-gray-300 text-gray-800 font-semibold py-3 rounded-full hover:bg-gray-100 transition">Choose Plan</a>
        </div>

        <!-- Plan 6: Classic Signature -->
        <div class="bg-gray-50 border border-gray-200 rounded-2xl p-8 flex flex-col hover:shadow-md transition duration-300 relative" data-aos="fade-up" data-aos-delay="250">
          <span class="absolute top-4 right-4 bg-brand-gold/20 text-brand-gold text-xs font-bold px-2 py-1 rounded">LIFETIME</span>
          <div class="mb-6"><h3 class="text-xl font-bold text-gray-900">ক্লাসিক সিগনেচার</h3><p class="text-sm text-gray-500 mt-1">One-time payment</p></div>
          <div class="mb-6"><span class="text-4xl font-bold text-gray-900">৳২৬,০০০</span><span class="text-sm text-gray-500 ml-1">/ Lifetime</span></div>
          <ul class="space-y-3 text-sm text-gray-600 mb-8 flex-grow">
            <li class="flex items-center gap-2"><i class="fas fa-check text-brand-red"></i> লাইফটাইম বায়োডাটা লিস্টিং</li>
            <li class="flex items-center gap-2"><i class="fas fa-check text-brand-red"></i> ডেডিকেটেড ম্যানেজার</li>
          </ul>
          <a href="https://wa.me/8801805412128?text=Hi!%20I%20want%20Classic%20Signature" class="block text-center bg-white border border-gray-300 text-gray-800 font-semibold py-3 rounded-full hover:bg-gray-100 transition">Choose Plan</a>
        </div>

      </div>
    </div>
  </section>

  <!-- Success Stories -->
  <section class="py-20 bg-gray-50" id="success">
   <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="flex flex-col md:flex-row justify-between items-center mb-10">
        <div><span class="text-brand-red font-bold tracking-widest uppercase text-xs mb-1 block">Blog</span><h2 class="text-3xl font-extrabold text-gray-900">Success Stories</h2></div>
    </div>
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
     <article class="news-card" data-aos="fade-up">
        <div class="news-img-wrapper"><img alt="Couple" src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEimrvf-pY4nRY24-Z-cWGSjjU5ejKzoRCj36rBhRso_qA774u2kfNC_bBSrHHIa6erGPygYTcsyx3QBIPzssruWleiD_6RG-kwfB54aELRRScjyqJajnKHE02xU0B9hVZlIhU9VqY1c32fvdCMhl32EzcdTaE96qZu8z610qjVv7MDZuISdAPcKcuu3qE4/s1600/1000161802.png" /><span class="news-category">Wedding</span></div>
        <div class="news-content">
            <div class="news-meta"><span><i class="far fa-calendar-alt"></i> Dec 12, 2023</span><span><i class="fas fa-map-marker-alt"></i> Dhaka</span></div>
            <h3 class="news-title">Rahim & Ayesha: A Banking Professional's Perfect Match</h3>
            <p class="news-excerpt">Finding a partner compatible with my banking profession was tough...</p>
            <a href="#" class="news-link">Read Full Story <i class="fas fa-long-arrow-alt-right"></i></a>
        </div>
     </article>
     <article class="news-card" data-aos="fade-up" data-aos-delay="50">
        <div class="news-img-wrapper"><img alt="Couple" src="https://storage.googleapis.com/a1aa/image/05280338-7cd4-4d6a-cca0-9be4f6ce807b.jpg" /><span class="news-category">NRI</span></div>
        <div class="news-content">
            <div class="news-meta"><span><i class="far fa-calendar-alt"></i> Jan 05, 2024</span><span><i class="fas fa-map-marker-alt"></i> London</span></div>
            <h3 class="news-title">Imran & Sadia: Trust Built Across Borders</h3>
            <p class="news-excerpt">Living abroad, verification was my main concern...</p>
            <a href="#" class="news-link">Read Full Story <i class="fas fa-long-arrow-alt-right"></i></a>
        </div>
     </article>
     <article class="news-card" data-aos="fade-up" data-aos-delay="100">
        <div class="news-img-wrapper"><img alt="Couple" src="https://storage.googleapis.com/a1aa/image/230448d7-53d2-41c6-e15c-4804c059e96c.jpg" /><span class="news-category">Love</span></div>
        <div class="news-content">
            <div class="news-meta"><span><i class="far fa-calendar-alt"></i> Feb 20, 2024</span><span><i class="fas fa-map-marker-alt"></i> Chittagong</span></div>
            <h3 class="news-title">Hasan & Nusrat: Found Match in 2 Months</h3>
            <p class="news-excerpt">The Gold Package helped us filter effectively...</p>
            <a href="#" class="news-link">Read Full Story <i class="fas fa-long-arrow-alt-right"></i></a>
        </div>
     </article>
    </div>
   </div>
  </section>

  <!-- CTA Section -->
  <section class="py-16 bg-brand-red relative overflow-hidden text-center text-white px-4">
    <div class="max-w-3xl mx-auto relative z-10">
        <h2 class="text-3xl md:text-4xl font-bold mb-4" data-aos="fade-up">Ready to Find Your Perfect Match?</h2>
        <p class="text-white/90 mb-8" data-aos-delay="100">Join thousands of happy couples who found their soulmates.</p>
        <div class="flex flex-col sm:flex-row gap-3 justify-center" data-aos-delay="200">
            <a class="btn-ui bg-white text-brand-red px-8 py-3 font-bold shadow-lg" href="https://forms.gle/U17sPuPLFYrznFoQ9">Register Free</a> 
            <a class="btn-ui border-2 border-white text-white px-8 py-3 font-bold hover:bg-white hover:text-brand-red transition" href="tel:+8809617179128">Call Us</a>
        </div>
    </div>
  </section>

  <!-- Back to Top Button -->
  <button class="fixed bottom-8 right-8 bg-brand-red text-white p-4 rounded-full shadow-2xl opacity-0 invisible transition-all duration-500 hover:bg-brand-dark z-50" id="backToTop">
    <i class="fas fa-arrow-up"></i>
  </button>

  <script>
        AOS.init({ duration: 800, once: true, offset: 50 });
        
        const backToTopButton = document.getElementById('backToTop');
        window.addEventListener('scroll', () => {
            if (window.scrollY > 500) { backToTopButton.classList.remove('opacity-0', 'invisible'); backToTopButton.classList.add('opacity-100', 'visible'); } 
            else { backToTopButton.classList.remove('opacity-100', 'visible'); backToTopButton.classList.add('opacity-0', 'invisible'); }
        });
        backToTopButton.addEventListener('click', () => { window.scrollTo({ top: 0, behavior: 'smooth' }); });

        const featureCards = document.querySelectorAll('.feature-card');
        const featureObserver = new IntersectionObserver((entries) => {
            entries.forEach((entry, index) => {
                if (entry.isIntersecting) { setTimeout(() => { entry.target.classList.add('visible'); }, index * 100); featureObserver.unobserve(entry.target); }
            });
        }, { threshold: 0.1 });
        featureCards.forEach(card => { featureObserver.observe(card); });

        document.addEventListener('DOMContentLoaded', () => {
            const slides = document.querySelectorAll('.slide');
            const dotsContainer = document.getElementById('sliderDots');
            let currentSlide = 0; let slideInterval;

            slides.forEach((_, index) => {
                const dot = document.createElement('div'); dot.classList.add('dot');
                if (index === 0) dot.classList.add('active');
                dot.addEventListener('click', () => goToSlide(index)); dotsContainer.appendChild(dot);
            });
            const dots = document.querySelectorAll('.dot');

            function updateSlides() {
                slides.forEach((slide, index) => {
                    slide.classList.remove('active'); dots[index].classList.remove('active');
                    if (index === currentSlide) { slide.classList.add('active'); dots[index].classList.add('active'); }
                });
            }
            function nextSlide() { currentSlide = (currentSlide + 1) % slides.length; updateSlides(); }
            function prevSlide() { currentSlide = (currentSlide - 1 + slides.length) % slides.length; updateSlides(); }
            function goToSlide(index) { currentSlide = index; updateSlides(); resetInterval(); }
            function resetInterval() { clearInterval(slideInterval); slideInterval = setInterval(nextSlide, 5000); }

            document.getElementById('prevBtn')?.addEventListener('click', () => { prevSlide(); resetInterval(); });
            document.getElementById('nextBtn')?.addEventListener('click', () => { nextSlide(); resetInterval(); });
            slideInterval = setInterval(nextSlide, 5000);
        });
    </script>
 </body>
</html>
