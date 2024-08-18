---
title: Registro
hide_title: true
sections:
  - type: content_section
    image: images/ESIME.webp
    image_id: esime
    image_alt: ESIME Unidad Zacatenco
  - type: form_section
    section_id: contact-form
    content: >-
      # Registro

      ### Semana de inducción 2025/1
      
      **ESIME Unidad Zacatenco.**     
      
      Agosto, 2024.


      USO OBLIGATORIO DE CUBREBOCAS EN TODO MOMENTO.

    form_id: Registro
    form_to: /induccion/done
    #Cambiar URL
    form_action: https://docs.google.com/forms/d/e/1FAIpQLSdvcUYDC3oSCIAJy4T5kUL0BJMY6Yz3BimhrP2YvODQAC97Ng/formResponse
    form_fields:
      - input_type: select
        #Cambiar codigo
        name: entry.172404053
        label: ¿Qué día dejaste tus papeles?
        default_value: Selecciona un día
        options:
          - Sábado, 17 de agosto
          - Domingo, 18 de agosto
          - Lunes, 19 de agosto
          - Martes, 20 de agosto
          - Miércoles, 21 de agosto
        is_required: true
      - input_type: text
      #Cambiar codigo
        name: entry.1550042724
        label: Ingresa tu boleta ó preboleta.
        default_value: 202530001 ó PE25031425 ó PP25041559 
        is_required: true
      - input_type: section
      - input_type: text
      #Cambiar codigo
        name: entry.467836427
        label: Nombre Completo
        extra: Empezando por apellidos
        default_value: López Castes José
        is_required: true
      - input_type: number
      #Cambiar codigo
        name: entry.776004186
        label: Edad
        default_value: 17
        is_required: true
      - input_type: email
      #Cambiar codigo
        name: entry.535706833
        label: Correo electrónico
        extra: Ingresa el correo que más utilices
        default_value: jose@gmail.com
        is_required: true
      - input_type: tel
      #Cambiar codigo
        name: entry.1657704661
        label: WhatsApp
        default_value: 55 4578 9805
        is_required: true
      - input_type: section
        label: Cuéntanos sobre ti.
      - input_type: text
      #Cambiar codigo
        name: entry.2088765041
        label: Escuela de procedencia
        default_value: CECyT - 6 "Miguel Othón de Mendizabal"
        is_required: true
      - input_type: select
      #Cambiar codigo
        name: entry.1666694072
        label: Estado de procedencia
        default_value: Selecciona una opción
        options:
          - Aguascalientes
          - Baja California
          - Baja California Sur
          - Chiapas
          - Chihuahua
          - Ciudad de México
          - Coahuila
          - Colima
          - Durango
          - Estado de México
          - Guanajuato
          - Guerrero
          - Hidalgo
          - Jalisco
          - Michoacán
          - Morelos
          - Nayarit
          - Nuevo León
          - Oaxaca
          - Puebla
          - Querétaro
          - Quintana Roo
          - San Luis Potosí
          - Sinaloa
          - Sonora
          - Tabasco
          - Tamaulipas
          - Tlaxcala
          - Veracruz
          - Yucatán
          - Zacatecas
        is_required: true
      - input_type: select
      #Cambiar codigo
        name: entry.831515350
        label: Nivel de inglés
        default_value: Selecciona una opción
        options:
          - Bajo
          - Intermedio
          - Avanzado
          - Tengo una certificación
          - No sé inglés
        is_required: true
      - input_type: select
      #Cambiar codigo
        name: entry.1580785789
        label: ¿Cuentas con una computadora propia?
        default_value: Selecciona una opción
        options:
          - 'Si'
          - 'No'
        is_required: true
      - input_type: select
      #Cambiar codigo
        name: entry.1464262659
        label: ¿Tienes alguna discapacidad?
        default_value: Selecciona una opción
        options:
          - Física
          - Visual
          - Auditiva
          - Cognitiva
          - Verbal
          - Psiquica
          - Múltiple
          - Otra
          - Ninguna
        is_required: true
      - input_type: select
      #Cambiar codigo
        name: entry.786722244
        label: ¿Qué red social utilizas más?
        default_value: Selecciona una opción
        options:
          - Facebook
          - X
          - Instagram
          - TikTok
          - Threads
          - Otra
        is_required: true
      - input_type: section
        label: 'Si tuvieras la oportunidad:'
      - input_type: select
      #Cambiar codigo
        name: entry.1719903588
        label: ¿Qué actividad cultural te gustaria aprender?
        default_value: Ninguna
        options:
          - Stand Up
          - Salsa Cubana
          - Pintura
          - Habilidades blandas
          - Fotografía
          - Dibujo
          - Danzas Polinesias
          - Creación literaria
          - Danza Folklórica
          - Cine
          - Crafting
          - Banda de guerra
          - Piano
      - input_type: select
      #Cambiar codigo
        name: entry.942675876
        label: ¿Qué actividad deportiva te gustaria practicar?
        default_value: Ninguna
        options:
          - Kendo
          - Box
          - Cheerleading
          - Fútbol
          - Basketball
          - Voleibol
          - Karate-Do
      - input_type: section
        label: Contacto en caso de emergencia.
      - input_type: text
      #Cambiar codigo
        name: entry.2093251114
        label: Nombre
        extra: Madre, padre o tutor
        default_value: López Castes José
        is_required: true
      - input_type: tel
      #Cambiar codigo
        name: entry.788475866
        label: Teléfono
        default_value: 55 4578 9805
        is_required: true
      - input_type: section
        label: Finalmente.
      - input_type: textarea
      #Cambiar codigo
        name: entry.894073424
        label: ¿Cómo te enteraste de la existencia de tu carrera y de la ESIME Unidad Zacatenco?
        default_value: Escribe en este espacio.
        is_required: true
      - input_type: checkbox
      #Cambiar codigo
        name: entry.1584644062
        label: >-
          Comprobé que mis datos son correctos y están bien escritos (correo electrónico, nombres y teléfono), además, doy veracidad a la información que he ingresado.
        is_required: true
    submit_label: Enviar
seo:
  title: Registro
  description: Semana de inducción 2025/1 ESIME Unidad Zacatenco.
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Registro
      keyName: property
    - name: 'og:description'
      value: Semana de inducción 2025/1 ESIME Unidad Zacatenco.
      keyName: property
    - name: 'og:image'
      value: images/seo.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Registro
    - name: 'twitter:description'
      value: Semana de inducción 2025/1 ESIME Unidad Zacatenco.
    - name: 'twitter:image'
      value: images/seo.png
      relativeUrl: true
layout: advanced
---
