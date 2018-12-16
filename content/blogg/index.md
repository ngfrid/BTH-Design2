---
views:
    main:
        template: anax/v2/article/default
        data:
            class: blog

    byline: false
    block-about: false
    article-toc: false

    blog-list:
        region: main
        template: anax/v2/blog-list/default
        sort: 2
        data:
            dateFormat: j F Y
            meta:
                type: toc
                orderby: publishTime
                orderorder: desc

    blog-toc:
        region: sidebar-right
        template: anax/v2/blog-toc/default
        sort: 2
        data:
            meta:
                type: copy
                view: blog-list

---
Niklas bild blogg
===========================

Bild blogg till kursen web design komom 05.

Till denna blogg var det kanske tänkt att gå ut och ta nya bilder, men eftersom jag är ganska lat och det dessutom konstant är kallt ochh blött ute så bestämde jag mig för att göra en blogg om en av mina hobbies. Så det blev modellbygge med bilder på mina modeller, det trevliga med det är att jag redan har en bunt med bilder på dem så att jag slipper gå ut och bli blöt och kall bara för lite bilder.

[FIGURE src="image/blogg_front.jpg?100%" class="" caption="Bismarck skala 1:200 midskepps sektion"]
