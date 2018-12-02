---
path: "/first-post"
date: "2018-12-02"
title: "Our First Post"
---

# First Post

Lorem ipsum dolor amet pitchfork try-hard put a bird on it farm-to-table ugh mixtape freegan ramps pork belly before they sold out. Poutine live-edge DIY, offal cred squid tumblr man bun knausgaard tote bag truffaut selfies mumblecore cliche four dollar toast. Kombucha cliche tumeric live-edge, meggings taiyaki cardigan subway tile mumblecore blog. Freegan VHS normcore sriracha whatever fam polaroid butcher. Fixie synth taiyaki dreamcatcher, succulents everyday carry truffaut chartreuse venmo freegan intelligentsia drinking vinegar. Pabst PBR&B plaid, keffiyeh narwhal pinterest gochujang dreamcatcher meh prism portland meggings 8-bit ethical franzen.

Vice narwhal venmo pop-up prism viral readymade meggings try-hard af truffaut hella scenester cliche tote bag. Pabst selvage blog distillery everyday carry portland sriracha pug lo-fi scenester fashion axe mlkshk occupy actually VHS. Salvia keytar air plant, fingerstache pour-over mixtape raclette offal synth man bun marfa succulents. XOXO pabst freegan iceland meditation offal semiotics franzen 8-bit direct trade wolf poke small batch roof party. Truffaut helvetica viral you probably haven't heard of them. Try-hard enamel pin edison bulb blog, jianbing master cleanse kale chips. Biodiesel af ugh forage meditation raclette unicorn cliche vinyl.

## Second Heading

Vinyl pork belly literally iceland, chillwave seitan gluten-free synth drinking vinegar tacos biodiesel banjo. Vinyl +1 listicle activated charcoal, flannel bushwick lo-fi ennui kogi marfa cronut. +1 fingerstache heirloom polaroid skateboard, sriracha slow-carb fanny pack affogato mixtape locavore jean shorts tilde chillwave vape. Chicharrones fingerstache messenger bag put a bird on it, umami fixie deep v bicycle rights. Gastropub kinfolk copper mug air plant. Intelligentsia paleo la croix sriracha truffaut trust fund tacos whatever narwhal chicharrones mlkshk. Cliche ugh messenger bag, copper mug ennui pork belly direct trade hoodie man braid.

## Third Heading

Crucifix deep v put a bird on it banh mi dreamcatcher small batch, iPhone VHS blog glossier viral asymmetrical plaid trust fund. Bespoke post-ironic kitsch artisan live-edge actually kogi cold-pressed knausgaard man bun pabst humblebrag umami. Waistcoat cray leggings semiotics tumblr. Man braid gluten-free tattooed deep v pork belly sustainable plaid beard ugh brunch drinking vinegar gochujang bespoke unicorn fashion axe. IPhone franzen pok pok hammock church-key 90's fixie viral air plant kombucha helvetica selfies keffiyeh.

Tattooed cronut master cleanse lo-fi pinterest palo santo. Swag meh bespoke, raw denim dreamcatcher PBR&B woke coloring book. Pug tattooed letterpress austin, synth air plant small batch. Chillwave sustainable coloring book occupy salvia +1 hammock vice hashtag etsy poke. Distillery ennui normcore lomo man bun blue bottle lumbersexual hoodie vice, truffaut migas tilde. Kitsch tote bag waistcoat, kickstarter activated charcoal retro XOXO helvetica letterpress. Kale chips leggings vice, iPhone bespoke kinfolk semiotics art party.

## Extra

* gatsby-transformer-remark

```
allMarkdownRemark {
    totalCount
    edges {
      node {
        html
        excerpt
        frontmatter {
          title
          date(formatString: "MMMM DD, YYYY")
          path
        }
      }
    }
  }
  ```

- allMarkdownRemark allows us to access the posts
- totalCount tells how many posts we have
- edges represents all the content
- node is one individual element which is part of the edges
- html converts the markdown post into real html
- excerpt shows a brief intro
- frontmatter contains info about the post