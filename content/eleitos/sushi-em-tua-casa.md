---
category: REI DO SUSHI
title: 03 SUSHI EM TUA CASA
image: https://dynamic-media-cdn.tripadvisor.com/media/photo-o/17/e8/57/1d/um-dos-nossos-menus-de.jpg?w=900&h=500&s=1
description: A prova de que a excelência não conhece fronteiras físicas. Focado
  exclusivamente no formato take-away, este espaço redefine o conceito de
  frescura na Cidade Berço, oferecendo aquela que é, consensualmente, a
  experiência de sushi mais sublime da região.
phone: 912 309 797
map_link: https://maps.app.goo.gl/MG6cTp1E5Z7V2Eeq8?g_st=ac
order_link: 'backend:   name: git-gateway   branch: main  media_folder: "images"
  # Onde as fotos que carregares vão ser guardadas public_folder:
  "/images"  collections:   - name: "eleitos"     label: "Os
  Eleitos"     folder: "content/eleitos"     create: true     slug:
  "{{title}}"     fields:       - { label: "Categoria", name: "category",
  widget: "string", hint: "Ex: A MELHOR FRANCESINHA" }       - { label: "Nome do
  Estabelecimento", name: "title", widget: "string" }       - { label: "Imagem
  de Destaque", name: "image", widget: "image" }       - { label: "Descrição",
  name: "description", widget: "text" }       - { label: "Telefone", name:
  "phone", widget: "string" }       - { label: "Link Google Maps", name:
  "map_link", widget: "string" }       - { label: "Link de Encomenda
  (Opcional)", name: "order_link", widget: "string", required: false }       - {
  label: "Nomeados", name: "nominees", widget: "string", hint: "Separados por •"
  }'
nominees: Império Sushi, Temple Guimarães, Formigas, Roiyaru Sushi House,
  LabRamen & Sushi Bar
---
