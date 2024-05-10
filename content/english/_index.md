---

########################### hero slider ############################
hero_slider:
  enable : true
  slider_item:
    # slider item
    - subtitle : "We help you to"
      title : "Implement project governance"
      content : "De-risk and protect your investment in delivering projects"
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
      title : "Apply Business Analysis"
      content : "Elicit proper requirements to deliver measurable benefits"
      bg_image_webp : "images/slider/banner-2.webp"
      bg_image : "images/slider/banner-2.jpg"
      animation : "fadeInDown" # animation select from : https://daneden.github.io/animate.css/
      button:
        enable : true
        label : "more details"
        link : "service/"
        animation : "zoomIn" # animation select from : https://daneden.github.io/animate.css/
        
    # slider item
    - subtitle : "We help you to"
      title : "Adopt Process Excellence"
      content : "Radically improve efficiency and productivity"
      bg_image_webp : "images/slider/banner-3.webp"
      bg_image : "images/slider/banner-3.jpg"
      animation : "fadeInLeft" # animation select from : https://daneden.github.io/animate.css/
      button:
        enable : true
        label : "more details"
        link : "service/"
        animation : "zoomIn" # animation select from : https://daneden.github.io/animate.css/
        
    # slider item
    - subtitle : "We help you to"
      title : "Manage Organisational Change"
      content : "Implement a rightsized change strategy"
      bg_image_webp : "images/slider/banner-4.webp"
      bg_image : "images/slider/banner-4.jpg"
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
    - name : "Project Governance"
      icon : "far fa-gem" # font-awesome 5 : https://fontawesome.com/icons/
      content : "Set-up or get back on track projects."
      
    # banner feature item loop
    - name : "Business Analysis"
      icon : "far fa-chart-bar" # font-awesome 5 : https://fontawesome.com/icons/
      content : "Define requirements with traceability to value."
      
    # banner feature item loop
    - name : "Process Excellence"
      icon : "far fa-lightbulb" # font-awesome 5 : https://fontawesome.com/icons/
      content : "Optimise processes to maximise value."
      
    # banner feature item loop
    - name : "Organisational Change"
      icon : "fas fa-tachometer-alt" # font-awesome 5 : https://fontawesome.com/icons/
      content : "Manage people side of change."


################################## about ####################################
about:
  enable : true
  subtitle : "About Us"
  title : "Established in 2009, our “Why” is a passion to help clients be calm and worry-free (or ZEN!) in delivering projects "
  content : "With over 25 years of digital transformation experience, our Founder Rowan Teh has seen the best and worse examples of project execution. He says:
  “Executing projects is as much an art than it is a science. You can apply the rigour of methodologies and systems, but without leadership, stakeholder management and intuition, you’re destined to fail. Zen Consulting provides the trusted advisor to ensure transformations are set-up for success.”"
  bg_image : "images/backgrounds/about-us-bg.png"
  bg_image_webp : "images/backgrounds/about-us-bg.webp"
  image_webp : "images/about/about-us.png"
  image : "images/about/about-us.png"
  button:
    enable : true;
    label : "more service"
    link : "service/"

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


################################# feature ############################################
feature:
  enable : true
  subtitle : "Why Choose Us"
  title : "Why They Choose Zen Consulting"
  image_webp : "images/feature/feature.jpg"
  image : "images/feature/feature.jpg"
  content : "What you see is what you get. Unlike other consulting outfits where the people selling are different from those delivering, you can rest assure the face you start with will be the same as the one delivering."
  feature_item:
    # feature item loop
    - name : "Seasoned Consultants"
      icon : "far fa-snowflake" # font-awesome 5 : https://fontawesome.com/icons/
      content : "Our consultants are experts and leaders in their field. They love what they do and they’re known for it."
      
    # feature item loop
    - name : "Trusted to Do the Right Thing"
      icon : "fas fa-code" # font-awesome 5 : https://fontawesome.com/icons/
      content : "Even if this means challenging your ideas, we engage to add immediate and ongoing value."

################################# service ############################################
service:
  enable : true
  section: "service"
  show_item : 3
  # service item comes from "content/*/service" folder

################################# team ##############################################
team:
  enable : false
  section: "team"
  show_item : 3
  # team member comes from "content/*/team" folder

################################# project ############################################
project:
  enable : false
  section: "project"
  show_item : 4
  button:
    enable : true
    label : "more projects"
    link : "project/"
  # project item comes from "content/*/project" folder

################################# testimonial #########################################
testimonial:
  enable : false
  subtitle : "Testimonials"
  title : "What Clients Are Say?"
  testimonial_item:
    # testimonial item loop
    - client_image : "images/testimonial/client-1.jpg"
      name : "Dominic Allen"
      designation : "Designer"
      content : "Lorem ipsum dolor sit amet, consectetur adipisicing elit sed eiusmod tempor incididunt ut labore dolore magna aliqua.enim ad minim veniam.quis nostrud exercitation ullamco laboris nis aliquip ex ea commodo consequat. duis aute irure dolor in reprehen."
      
    # testimonial item loop
    - client_image : "images/testimonial/client-2.jpg"
      name : "Alex Pitt"
      designation : "Designer"
      content : "Lorem ipsum dolor sit amet, consectetur adipisicing elit sed eiusmod tempor incididunt ut labore dolore magna aliqua.enim ad minim veniam.quis nostrud exercitation ullamco laboris nis aliquip ex ea commodo consequat. duis aute irure dolor in reprehen."

    # testimonial item loop
    - client_image : "images/testimonial/client-3.jpg"
      name : "John Doe"
      designation : "Designer"
      content : "Lorem ipsum dolor sit amet, consectetur adipisicing elit sed eiusmod tempor incididunt ut labore dolore magna aliqua.enim ad minim veniam.quis nostrud exercitation ullamco laboris nis aliquip ex ea commodo consequat. duis aute irure dolor in reprehen."


################################# blog ################################################
cta:
  enable : true
  title : "Zen Consulting For Stress-Free Project Delivery"
  bg_image_webp : "images/backgrounds/cta-lg.webp"
  bg_image : "images/backgrounds/cta-lg.jpg"
  button:
    enable : true
    label : "get a quote"
    link : "contact/"

################################# blog ################################################
blog:
  enable : false
  section : "blog"
  show_item : 3
  # blog post comes from "content/*/blog" folder

---