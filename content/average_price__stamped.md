+++
title = "Stamped Concrete"
path = "/average-price/stamped"
template = "landing_page.html"

[extra]
heading = "Stamped Concrete"
subheading = "Fully Insured. Friendly Service. Based in Schaumburg, IL. Neat concrete. Call Now."
do_not_index = true
+++

{{ service_tiles(path="data/services.json") }}

{% left_image_right_text(
     image_path="images/concrete_contractor_for_hire.jpg",
     image_description="Concrete Contractor in Schaumburg For Hire",
     heading="How It Works",
     intro="A simple process to solve your Concrete problems!") %}

1. **Inspect** - we visit the property and recommend the solution to your problem
2. **Quote** - provide you with an instant quote
3. **Book** - schedule the appointment for a day and time that suits you
4. **Work** - we'll perform the work, leaving you with a much better home
5. **Pay** - we accept all major credit cards
6. **Enjoy** - you've just given your property a new lease of life - time to enjoy it again!

{% end %}

{{ before_and_after(
     path="data/our_work.json",
     heading="Our Work",
     show_phone_cta=false) }}

{{ reviews(
     path="data/reviews.json",
     heading="Happy Customers",
     show_phone_cta=true) }}

{{ contact_form_over_image(
     heading="Get a Free Quote Today",
     submit_cta="Get In Touch Now",
     background_image_url="images/get_a_quote.jpg",
     background_image_alt="Stamped Concrete") }}

{{ cta_block(
     heading="Stamped Concrete",
     subheading="Get in Touch For Concrete Today!") }}