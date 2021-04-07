---
title: Home
white_header: true
sections:
  - type: hero_section
    section_id: hero_section
    background_image: images/header.jpg
    background_image_opacity: 65
    content: "# Faites vous livrer de magnifiques plantes"
    actions:
      - type: action
        title: Voir tous les article
        url: /store
        style: primary
        arrow: true
  - type: featured_products_section
    title: Meilleures ventes
    section_id: best_sellers_section
    light_title: true
    icon: true
    featured_products:
      - src/pages/products/plant1.md
      - src/pages/products/plant3.md
      - src/pages/products/plant5.md
      - src/pages/products/plant7.md
  - type: featured_categories_section
    section_id: featured_categories_section
    featured_categories:
      - src/pages/category/bigplants.md
      - src/pages/category/cactuses.md
  - type: testimonials_section
    section_id: testimonials_section
    title: Témoignages
    testimonials:
      - text: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent vel
          mauris urna. Fusce eget turpis pellentesque, congue felis eget,
          maximus.
        author:
          name: John Dope
          location: Colorado, USA
      - text: " Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer iaculis
          lectus eu dui pretium rutrum. Donec ornare ex non elementum."
        author:
          name: Major Payne
          location: VA, USA
  - type: promotion_section
    section_id: promotion_section
    title: Un espace de mise en avant de produit
    subtitle: 50 €
    image: images/promo.jpg
    background_image: images/leaf.svg
    cta:
      type: action
      title: Découvrir
      url: /store
      style: secondary
      arrow: true
template: home
---
