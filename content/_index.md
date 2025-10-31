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
        <center>
        <b>Herzlich willkommen auf unserer Internet-Seite!</b><br/>
        </center>
        <br/>
        "Schauen Sie sich bitte auf diesen Seiten um; Fragen beantworte ich gerne persönlich."<br/>
        <small>-- Peter Meyn,<br/> 
        Goldschmiedemeister, Juwelenfasser und Uhrmacher</small>
        <br/>
        <br/>
        <b>Meisterbetrieb</b><br/>
        Handwerkskammer Lübeck<br/>
        Betriebsnr. 2120544148<br/>
        UStIdNr: DE199869177<br/>
 
        
  
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
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
