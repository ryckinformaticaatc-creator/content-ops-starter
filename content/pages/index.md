---
title: Ryckinformatica
slug: /
sections:
  - type: GenericSection
    title:
      text: Ryckinformatica
      color: text-dark
      type: TitleBlock
    subtitle: Tu mejor opción para soluciones informáticas
    text: >
      Empresa dedica a ofrecer soluciones informáticas a su empresa con los mas
      altos estándares de calidad y servicio
    actions: []
    media:
      url: /images/1000056782-4.png
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
  - type: FeaturedItemsSection
    title:
      text: Nuestros
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Servicios
    items:
      - type: FeaturedItem
        title: Asesoria Aspel
        subtitle: ''
        text: |
          Servicio personalizado en sistemas, infraestructura sistemas Aspel.

          *   Nomina.

          *   Contabilidad.

          *   Facturación Electrónica.

          *   Sistema de inventarios.
        actions: []
        elementId: null
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
            textAlign: left
        image:
          type: ImageBlock
          altText: Lightning bolt symbol on red background
          elementId: ''
          url: /images/aspel.png
          styles:
            self:
              borderRadius: x-large
      - title: Mantenimiento
        subtitle: ''
        text: |+
          Servicio esquipo de computo.

          *   Venta equipo de computo.

          *   Consumibles.

          *   Mantenimiento Preventivo

          *   Mantenimiento Correctivo

        image:
          url: >-
            /images/Default_specialized_computer_technician_working_hard_to_solve_1
            (2).jpg
          altText: Featured icon two
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            textAlign: left
            justifyContent: center
        type: FeaturedItem
      - title: Redes
        subtitle: ''
        text: |+
          Instalación, diagnostico de redes.

          *   Cableado

          *   Wifi

          *   Routers

          *   Access Point

          *   Switchs

        image:
          url: >-
            /images/Flux_Dev_A_sleek_computer_rack_stands_tall_with_a_24port_switc_1.jpg
          altText: Featured icon three
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
        type: FeaturedItem
      - type: FeaturedItem
        title: Dominios web
        tagline: ''
        subtitle: ''
        text: |+
          *   Registro de dominios web

          *   Correo Electronico

        image:
          type: ImageBlock
          url: >-
            /images/Default_specialized_computer_technician_working_hard_to_solve_1
            (1).jpg
          altText: Placeholder text
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
    actions: []
    elementId: ''
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pb-16
          - pt-16
          - pl-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
  - subtitle: Nuestros clientes
    images:
      - altText: Asesores Veracruzanos
        type: ImageBlock
        url: /images/ASSVEROK2024.png
      - type: ImageBlock
        url: /images/hero2.svg
        altText: Image alt text placeholder
        elementId: ''
        styles:
          self:
            borderRadius: medium
    motion: move-to-left
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
    type: ImageGallerySection
  - title:
      text: Contacta con nosotros
      color: text-dark
      type: TitleBlock
    subtitle: ''
    text: ''
    media:
      fields:
        - name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Your message
          width: full
          type: TextareaFormControl
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: FormBlock
      submitButton:
        type: SubmitButtonFormControl
        label: Enviar
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: null
    badge:
      label: Contacto
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    type: GenericSection
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
isDraft: false
---
