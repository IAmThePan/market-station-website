Directory of Pages:
- [x] HomePage
- Apartments:
  - [ ] Floor Plans
    - [o] Get new floor plan images.
      - Cheryl will look for them
      - In the meantime I will edit the existing photos.
    - [ ] Me: Make it so the page doesn't get extended on mobile.
    - [ ] Me: Make images bigger when you click on them
  - [x] Amenities
  - [x] Location
- [x] Photo Gallery
  - ToDo: How do I put all the Gallery Photos inside an `/images` folder and access them with `.Page.Resources`?
- [x] Apply
- [x] Resident Portal
- [x] Contact Us
  - [x] Contact Form not necessary

Questions for Dad:
- [ ] Verify the description for the site.
- [ ] Do you want a Spanish version as well as English?

My ToDos:
- [ ] Make the mobile header menu open with a transition
- [ ] Make the mobile apartments menu open with a transition
- Gallery:
  - [x] Rename photos in Gallery
  - [ ] Scroll between gallery photos with a transition
- [ ] Move static images to content folder
- [ ] Update / Verify site.webmanifest saves website correctly
- [ ] Make a 404 page
- [ ] Create separate repository for Theme, link into website repository
- [ ] Choose a license for theme, update `theme.toml`
- [ ] Verify site description in `config.toml`. also email.
- CSS:
  - [ ] Convert CSS to SCSS and compile all theme SCSS files into one CSS file for import
  - [ ] Separate Theme CSS from Site CSS (diferentiate along Classes used in Theme/Not)
    - [ ] Shortcode classes not used in theme should be defined in site's CSS only
    - [ ] Define all Helper Classes in Site CSS only.
    - [ ] iframe border-color set by Site Variable, not hard coded inline.
  - [ ] Create a colors.scss file in the Site Folder that the Theme can use.
  - [ ] Import ShortCode CSS from Shortcode, and limit import to one time
  - [ ] Use the same Header Menu Links in big and on mobile
