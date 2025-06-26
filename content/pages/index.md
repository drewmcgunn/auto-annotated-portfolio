---
type: PageLayout
title: Drew McGunn - Author Website
sections:
  - elementId: home
    colors: colors-f
    backgroundSize: full
    title: A System Crashed. A Life Rebooted.
    subtitle: >-
      Dive into the new LitRPG series from Drew McGunn. "A Hard Reset" is the
      beginning of an epic adventure in the System Integration Chronicles.
    actions:
      - type: Button
        label: Buy on Amazon
        url: 'https://www.amazon.com/Hard-Reset-System-Integration-Chronicles-ebook/dp/B0FDYNSJ5W'
        style: primary
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
      actions:
        justifyContent: center
    type: HeroSection
  # - type: FeaturedProjectsSection # This section is temporarily hidden. We will add it back once we create the individual project pages.
  #   elementId: books
  #   colors: colors-f
  #   subtitle: My Books
  #   projects:
  #     - content/pages/projects/a-hard-reset.md
  #     - content/pages/projects/lone-star-reloaded.md
  #   actions:
  #     - type: Link
  #       label: See all on Amazon
  #       url: 'https://www.amazon.com/stores/Drew-McGunn/author/B09QF2LCY3'
  #   styles:
  #     self:
  #       width: wide
  #       padding:
  #         - pt-24
  #         - pb-24
  #         - pl-4
  #         - pr-4
  #       justifyContent: center
  #     subtitle:
  #       textAlign: center
  - type: CtaSection
    elementId: about
    colors: colors-f
    title: About the Author
    text: >-
      Drew McGunn is a writer of thrilling what-ifs and epic adventures. After
      completing the seven-book Alt-History saga, "The Lone Star Reloaded," he
      has ventured into the digital realms of LitRPG with his new series, "The
      System Integration Chronicles."
    actions: []
    styles:
      self:
        width: wide
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
  # - type: FeaturedPostsSection # This section is temporarily hidden. We will add it back once we create the individual blog post pages.
  #   elementId: blog
  #   colors: colors-f
  #   variant: variant-d
  #   subtitle: Latest News
  #   posts:
  #     - content/pages/blog/post-one.md
  #     - content/pages/blog/post-two.md
  #     - content/pages/blog/post-three.md
  #   actions:
  #     - type: Link
  #       label: See all posts
  #       url: /blog
  #   styles:
  #     self:
  #       width: wide
  #       padding:
  #         - pt-28
  #         - pb-48
  #         - pl-4
  #         - pr-4
  - type: ContactSection
    colors: colors-f
    elementId: contact
    backgroundSize: full
    title: Join the Adventure
    text: >-
      Get updates on new releases, exclusive content, and behind-the-scenes
      news. No spam, ever.
    form:
      type: FormBlock
      elementId: newsletter-form
      fields:
        - name: email
          label: Email
          hideLabel: true
          placeholder: Enter your email
          isRequired: true
          width: full
          type: EmailFormControl
      submitLabel: Sign Up
    styles:
      self:
        width: narrow
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
---

