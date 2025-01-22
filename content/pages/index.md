---
type: PageLayout
title: Home
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg1.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: I’m a photographer and artist.
    subtitle: "I am a freelance photographer who also involved in various art-related projects, with a passion for capturing moments and showing meaningful exhibitions.\_I specialize more in events, concerts, and outdoor shoots. I love to record every precious moment because it means the most to you."
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
        borderWidth: 2
        borderStyle: dotted
        borderRadius: large
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
    actions: []
    text: >+
      #### These are some of the projects I've worked on before and hopefully
      get you interested in them.

  - type: DividerSection
    title: Divider
    elementId: ''
    styles:
      self:
        width: full
        padding:
          - pt-36
          - pb-36
        justifyContent: center
        borderWidth: 1
  - type: CtaSection
    title: Wedding Photography
    text: >+
      Check out some of the amazing weddings I have covered, capturing
      unforgettable moments.

    actions:
      - type: Button
        label: Learn More
        altText: ''
        url: >-
          https://www.canva.com/design/DAF_syX5PLY/rAJxRBf_LIMX6crSK6n2Bw/view?utm_content=DAF_syX5PLY&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h05ba2dedbe
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
    colors: colors-f
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: CtaSection
    title: Concert Photography
    text: |+
      Explore my work in capturing the energy and emotion of live performances.

    actions:
      - type: Button
        label: Learn More
        altText: ''
        url: >-
          https://www.canva.com/design/DAGbzlF8hGE/5bYaRNi5GXApDuU1yUKpNw/view?utm_content=DAGbzlF8hGE&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h498add69fa
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
    colors: colors-f
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: CtaSection
    title: Graduation Photography
    text: >+
      Discover graduations with stunning photos that showcase your success and
      excitement.

    actions:
      - type: Button
        label: Learn More
        altText: ''
        url: >-
          https://www.canva.com/design/DAF0ZTcXlKI/BDN-EgAQWavjh8eHdvVguQ/view?utm_content=DAF0ZTcXlKI&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h203c09a5b9
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
    colors: colors-f
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: "Got an interesting project? Tell me more...\U0001F4AC"
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: 1/2
          type: EmailFormControl
        - name: address
          label: Address
          hideLabel: true
          placeholder: Address
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: updatesConsent
          label: Sign me up to recieve updates
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: "Submit \U0001F680"
      styles:
        submitLabel:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
---
