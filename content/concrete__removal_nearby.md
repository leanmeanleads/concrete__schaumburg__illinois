+++
title = "Concrete Removal Near You"
path = "/concrete/removal-nearby"
template = "landing_page.html"
description = "Call (224) 477-2663 for concrete removal near you. We offer competitive rates and excellent service to ensure you get a job well done."

[extra]
heading = "Concrete Removal Near You"
subheading = "Remove Your Old Concrete. Fully Insured. Friendly Service. Based in Schaumburg, IL. Call Now."
+++

{{ service_tiles(path="data/services.json") }}

{% left_image_right_text(
     image_path="images/concrete_contractor_for_hire.jpg",
     image_description="Concrete Removal in Schaumburg For Hire",
     heading="How It Works",
     intro="A simple process to remove your old concrete!") %}

1. **Inspect** - we visit the property and recommend the best way to remove your old concrete
2. **Quote** - provide you with an instant quote
3. **Book** - schedule the concrete removal appointment for a day and time that suits you
4. **Work** - we'll remove your old concrete, leaving you with a clean slate for fresh concrete
5. **Pay** - we accept all major credit cards
6. **Enjoy** - you've just given your concrete a new lease of life - time to enjoy it again!

{% end %}

{{ before_and_after(
     path="data/our_work.json",
     heading="Our Work",
     show_phone_cta=false) }}

{{ reviews(
     path="data/reviews.json",
     heading="Happy Removal Customers",
     show_phone_cta=true) }}

{{ contact_form_over_image(
     heading="Get a Free Quote Today",
     submit_cta="Get In Touch Now",
     background_image_url="images/get_a_quote.jpg",
     background_image_alt="Concrete Removal Near You") }}

{{ cta_block(
     heading="Concrete Removal Near You",
     subheading="Get in Touch For Concrete Removal Today!") }}