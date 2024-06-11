---

########################### hero slider ############################
hero_slider:
  enable : true
  slider_item:
  
    # slider item
    - subtitle : "We help you to"
      title : "Elicit Measurable Requirements"
      content : "Leverage our deep Business Analysis expertise"
      bg_image_webp : "images/slider/banner-4.webp"
      bg_image : "images/slider/banner-4.jpg"
      animation : "fadeInDown" # animation select from : https://daneden.github.io/animate.css/
      button:
        enable : true
        label : "more details"
        link : "service/"
        animation : "zoomIn" # animation select from : https://daneden.github.io/animate.css/

    # slider item
    - subtitle : "We help you to"
      title : "Optimise Processes for Efficiency"
      content : "Leverage our Lean Six Sigma expertise"
      bg_image_webp : "images/slider/banner-2.webp"
      bg_image : "images/slider/banner-2.jpg"
      animation : "fadeInLeft" # animation select from : https://daneden.github.io/animate.css/
      button:
        enable : true
        label : "more details"
        link : "service/"
        animation : "zoomIn" # animation select from : https://daneden.github.io/animate.css/

    # slider item
    - subtitle : "We help you to"
      title : "Govern Projects for Success"
      content : "Leverage our Seasoned Project Management expertise"
      bg_image_webp : "images/slider/banner-1.webp"
      bg_image : "images/slider/banner-1.jpg"
      animation : "fadeInUp" # animation select from : https://daneden.github.io/animate.css/
      button:
        enable : true
        label : "more details"
        link : "service/"
        animation : "zoomIn" # animation select from : https://daneden.github.io/animate.css/
        
    # slider item
    - subtitle : "We help you to"
      title : "Transition People for Change"
      content : "Leverage our Organisational Change expertise"
      bg_image_webp : "images/slider/banner-3.webp"
      bg_image : "images/slider/banner-3.jpg"
      animation : "fadeInRight" # animation select from : https://daneden.github.io/animate.css/
      button:
        enable : true
        label : "more details"
        link : "service/"
        animation : "zoomIn" # animation select from : https://daneden.github.io/animate.css/
        
################################## banner feature ############################
banner_feature:
  enable : true
  # Max use 4 item
  feature_item:
     # banner feature item loop
    - name : "Business Analysis"
      icon : "fas fa-search-dollar" # font-awesome 5 : https://fontawesome.com/icons/
      content : "Elicit requirements with measurable value"

    # banner feature item loop
    - name : "Process Excellence"
      icon : "fas fa-project-diagram" # font-awesome 5 : https://fontawesome.com/icons/
      content : "Optimise for greater efficiency & productivity"
      
    # banner feature item loop
    - name : "Project Governance"
      icon : "fas fa-landmark" # font-awesome 5 : https://fontawesome.com/icons/
      content : "Set-up or get back on track projects"
      
    # banner feature item loop
    - name : "Organisational Change"
      icon : "fas fa-hands-helping" # font-awesome 5 : https://fontawesome.com/icons/
      content : "Implement a rightsized change strategy"

      
################################## about ####################################
about:
  enable : true
  subtitle : "About Us"
  title : "Established in 2009, our “Why” is a passion to help clients reduce the worry in transformations, with 'ZEN'-like calm"
  content : "With over 25 years of digital transformation experience, our Founder Rowan Teh has seen the best and worse examples of projects. He says,
  *“executing projects is as much an art than it is a science. You can apply the rigour of methodologies and systems, but without leadership, stakeholder management and intuition, you’re destined to fail.”* Zen Consulting provides the trusted advisor to ensure transformations are set-up for success."
  bg_image : "images/backgrounds/about-us-bg.png"
  bg_image_webp : "images/backgrounds/about-us-bg.webp"
  image_webp : "images/about/about-us.png"
  image : "images/about/about-us.png"
  button:
    enable : true;
    label : "read more"
    link : "about/"

################################## funfacts ###############################
funfacts :
  enable : true
  funfacts_item :
    # fanfacts item loop
    - name : "Projects Completed"
      count : "30"
      icon : "fas fa-bullseye" # font-awesome 5 : https://fontawesome.com/icons/
      
    # fanfacts item loop
    - name : "Years Established"
      count : "15"
      icon : "far fa-calendar-alt" # font-awesome 5 : https://fontawesome.com/icons/
      
    # fanfacts item loop
    - name : "Years Experience"
      count : "25"
      icon : "fas fa-award" # font-awesome 5 : https://fontawesome.com/icons/
      
    # fanfacts item loop
    - name : "Customers Satisfied"
      count : "50"
      icon : "far fa-smile" # font-awesome 5 : https://fontawesome.com/icons/

################################# testimonial #########################################
testimonial:
  enable : true
  subtitle : "Testimonials"
  title : "What Clients Say"
  testimonial_item:
    # testimonial item loop
    - client_image : "images/testimonial/panpac.jpg"
      name : "Ross McMillan"
      designation : "Chief Financial Officer, Pan Pac"
      content : "Rowan has always given balanced, and considered advice based on his wide experience in ERP Implementations. His ability to give good governance and risk advice has been a vital cog in the Project’s success. Also his ability to help with practical and pragmatic advice for BAU has been much appreciated."

################################# feature ############################################
feature:
  enable : true
  subtitle : "Why Choose Us"
  title : "Make the Right Choice"
  image_webp : "images/feature/feature-1.webp"
  image : "images/feature/feature-1.jpg"
  content : "What you see is what you get. Unlike other consulting firms where the people selling are different from those delivering, you can rest assured the person you start with will be with you on your journey."
  feature_item:
    # feature item loop
    - name : "Seasoned Consultants"
      icon : "fas fa-chalkboard-teacher" # font-awesome 5 : https://fontawesome.com/icons/
      content : "Our consultants are experts and leaders in their field. They love what they do and they’re known for it."
      
    # feature item loop
    - name : "Trusted to Do the Right Thing"
      icon : "fas fa-hand-holding-heart" # font-awesome 5 : https://fontawesome.com/icons/
      content : "Even if this means challenging your ideas, we engage to add immediate and ongoing value."

################################# service ############################################
service:
  enable : true
  section: "service"
  show_item : 4
  # service item comes from "content/*/service" folder

################################# team ##############################################
team:
  enable : false
  section: "team"
  show_item : 5
  # team member comes from "content/*/team" folder

################################# project ############################################
project:
  enable : false
  section: "project"
  show_item : 6
  button:
    enable : true
    label : "more projects"
    link : "project/"
  # project item comes from "content/*/project" folder

################################# blog ################################################
cta:
  enable : true
  title : "Zen Consulting For Worriless Project Delivery"
  bg_image_webp : "images/backgrounds/cta-lg.webp"
  bg_image : "images/backgrounds/cta-lg.jpg"
  button:
    enable : true
    label : "Contact Us"
    link : "contact/"

################################# blog ################################################
blog:
  enable : false
  section : "blog"
  show_item : 7
  # blog post comes from "content/*/blog" folder

---