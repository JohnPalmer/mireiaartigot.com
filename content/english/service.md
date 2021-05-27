---
title: "Service"
description: "this is meta description"
bg_image: "images/feature-bg.jpg"
layout: "service"
draft: false


########################### about service #############################
about:
  enable : true
  title : "Creative UX/UI Design Agency"
  content : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptate soluta corporis odit, optio
          cum! Accusantium numquam ab, natus excepturi architecto earum ipsa aliquam, illum, omnis rerum, eveniet
          officia nihil. Eum quod iure nulla, soluta architecto distinctio. Nesciunt odio ullam expedita, neque fugit
          maiores sunt perferendis placeat autem animi, nihil quis suscipit quibusdam ut reiciendis doloribus natus nemo
          id quod illum aut culpa perspiciatis consequuntur tempore? Facilis nam vitae iure quisquam eius harum
          consequatur sapiente assumenda, officia voluptas quas numquam placeat, alias molestias nisi laudantium
          nesciunt perspiciatis suscipit hic voluptate corporis id distinctio earum. Dolor reprehenderit fuga dolore
          officia adipisci neque!"
  image : "images/company/company-group-pic.jpg"


########################## featured service ############################
featured_service:
  enable : true
  service_item:
    # featured service item loop
    - name : "Interface Design"
      icon : "ion-erlenmeyer-flask"
      color : "primary"
      content : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Saepe enim impedit repudiandae omnis est temporibus."
      
    # featured service item loop
    - name : "Product Branding"
      icon : "ion-leaf"
      color : "primary-dark"
      content : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Saepe enim impedit repudiandae omnis est temporibus."
      
    # featured service item loop
    - name : "Game Development"
      icon : "ion-lightbulb"
      color : "primary-darker"
      content : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Saepe enim impedit repudiandae omnis est temporibus."

      
############################# Service ###############################
service:
  enable : true
  title : "Curriculum Vitae"
  description : ""
  button:
    enable : true
    label : "Download CV"
    link : "project"

  service_item:
    # service item loop
    - icon : ion-university #ionicon pack v2 : https://ionicons.com/v2/ #ionicon pack v2 : https://ionicons.com/v2/
      name: Education
      content: "JSD, Cornell Law School<br>LLM, Cornell Law School<br>Law Degree, UPF<br>BA Economics, UPF<br>BA Music, Conservatory of Barcelona"

    # service item loop
    - icon : ion-briefcase #ionicon pack v2 : https://ionicons.com/v2/ #ionicon pack v2 : https://ionicons.com/v2/
      name: Current Employment
      content: "Ramon y Cajal Researcher, UPF Law School<br>Affiliated Professor of International Economics, ESCI-UPF"

    # service item loop
    - icon : ion-hammer #ionicon pack v2 : https://ionicons.com/v2/ #ionicon pack v2 : https://ionicons.com/v2/
      name: Project Leadership  
      content: "Principal Investigator, UPF, for <a href='https://www.fricore.eu/'>Fundamental Rights in Courts and Regulation (FricoRe) (JUST/2017/Action Grant)</a>"


      
############################# call to action #################################
cta:
  enable : true
  # call to action content comes from "data/*/homepage.yml"

---
