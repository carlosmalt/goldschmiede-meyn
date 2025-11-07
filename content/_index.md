---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Goldschmiede Meyn
      image:
        filename: team.jpeg
      text: |
        ## Herzlich Willkommen auf unserer Internetseite!
        >Schauen Sie sich bitte auf diesen Seiten um; Fragen beantworte ich gerne persönlich.  

        {{% mention admin %}}, Goldschmiedemeister, Juwelenfasser und Uhrmacher

        ### Meisterbetrieb
        Handwerkskammer Lübeck  
        Betriebsnr. 2120544148  
        UStIdNr: DE199869177  

        {{< cta cta_text="Aktuelles" cta_link="/post" >}}
        {{< cta cta_text="Kontakt" cta_link="/contact" >}}
        {{< cta cta_text="Team" cta_link="/people" >}}
       

  
  - block: collection
    content:
      title: Aktuelles
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'

---
