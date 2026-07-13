## 🤖 [Messe Düsseldorf Exhibitor List Scraper](https://apify.com/skython/messe-duesseldorf-exhibitor-list-scraper)

Simple web scraper for extracting exhibitor data from trade show exhibitor lists provided by **Messe Düsseldorf**. Easily scrape company profiles including **company details, websites, social media links, product categories, contact persons and more**. 

Ideal for **B2B lead generation, market research, event networking, and competitive analysis**. Supports multiple **Messe Düsseldorf** exhibition websites with a consistent HTML structure.

> [Apify](https://apify.com/) is a cloud platform and marketplace for web scraping and automation tools.

---

## Contents

- [Features](#features)

- [Use Cases](#use-cases)

- [Supported Website Structure](#supported-website-structure)

- [Supported Messe Düsseldorf Events (Exhibitor Lists)](#supported-messe-düsseldorf-events-exhibitor-lists)

- [Testing Exhibitor List URLs](#testing-exhibitor-list-urls-for-free)

- [Exhibitor List Scraper - All-In-One Version](#exhibitor-list-scraper---all-in-one-version)

- [Data Fields](#data-fields)

- [Example Output](#example-output)

- [My Other Exhibitor List Scrapers](#my-other-exhibitor-list-scrapers)

---

## Features

- Scrape all exhibitor profiles from supported Messe Düsseldorf event websites

- Extract detailed data from every exhibitor profile page

- Company primary information (address, email, phone, website)

- Social media links (LinkedIn, Facebook, Instagram, Twitter, YouTube)

- Contact person details

- Product categories with full hierarchical structure

- Two output formats (Single-Row & Multi-Row)

- Multi-Row format for Excel-friendly product category filtering

- Export to JSON, CSV, and Excel

---

## Use Cases

- **B2B Lead Generation:** Build targeted contact lists for marketing and sales outreach. 

- **Market Research:** Analyze exhibitors by product categories, brands, and sectors.  

- **Event Networking:** Familiarize yourself with exhibitors before attending trade fairs.  

- **Competitive Analysis:** Track competitor participation and product focus areas.

---

## Supported Website Structure

- This scraper is designed to extract data from exhibitor directories with the same HTML structure as the supported Messe Düsseldorf exhibitor lists below.

- Exhibitor listing page URLs should contain `/vis/v1/`.

- Take a look at some of the event websites from the below list. Your event website URL might be in that list.

- If you are not sure about if this actor is capable of scraping your event URL, test it with [**Exhibitor List Scrapers URL Tester**](https://apify.com/skython/exhibitor-list-scrapers-router) actor.

---

## Supported Messe Düsseldorf Events (Exhibitor Lists)

> The following partial list includes Messe Düsseldorf exhibitor directory URLs that have been tested so far. Other Messe Düsseldorf events or different events with the same website structure may also be supported.

> Some event URLs may have been updated or canceled entirely; please check them before using.

- [A+A 2025 Exhibitor List – aplusa-online.com](https://www.aplusa-online.com/vis/v1/en/search?ticket=g_u_e_s_t&_query=&f_type=profile)

- [Beauty Duesseldorf 2026 Exhibitor List – beauty-duesseldorf.com](https://www.beauty-duesseldorf.com/vis/v1/en/search?ticket=g_u_e_s_t&_query=&f_type=profile)

- [Boot Duesseldorf 2026 Exhibitor List – boot.com](https://www.boot.com/vis/v1/en/search?ticket=g_u_e_s_t&_query=&f_type=profile)

- [Caravan Salon Duesseldorf 2025 Exhibitor List – caravan-salon.com](https://www.caravan-salon.com/vis/v1/en/search?ticket=g_u_e_s_t&_query=&f_type=profile)

- [COMPAMED & MEDICA 2025 Exhibitor List – compamed-tradefair.com](https://www.compamed-tradefair.com/vis/v1/en/search?ticket=g_u_e_s_t&_query=&f_type=profile)

- [EuroCIS 2025 Exhibitor List – eurocis-tradefair.com](https://www.eurocis-tradefair.com/vis/v1/en/search?ticket=g_u_e_s_t&_query=&f_type=profile)

- [EuroShop 2026 Exhibitor List – euroshop-tradefair.com](https://www.euroshop-tradefair.com/vis/v1/en/search?ticket=g_u_e_s_t&_query=&f_type=profile)

- [GIFA 2023 Exhibitor List – gifa.com](https://www.gifa.com/vis/v1/en/search?ticket=g_u_e_s_t&_query=&f_type=profile)

- [glasstec 2024 Exhibitor List – glasstec-online.com](https://www.glasstec-online.com/vis/v1/en/search?ticket=g_u_e_s_t&_query=&f_type=profile)

- [interpack 2026 Exhibitor List – interpack.com](https://www.interpack.com/vis/v1/en/search?ticket=g_u_e_s_t&_query=&f_type=profile)

- [MEDICA & COMPAMED 2025 Exhibitor List – medica-tradefair.com](https://www.medica-tradefair.com/vis/v1/en/search?ticket=g_u_e_s_t&_query=&f_type=profile)

- [METEC 2023 Exhibitor List – metec-tradefair.com](https://www.metec-tradefair.com/vis/v1/en/search?ticket=g_u_e_s_t&_query=&f_type=profile)

- [NEWCAST 2023 Exhibitor List – newcast.com](https://www.newcast.com/vis/v1/en/search?ticket=g_u_e_s_t&_query=&f_type=profile)

- [K 2025 Exhibitor List – k-online.com](https://www.k-online.com/vis/v1/en/search?ticket=g_u_e_s_t&_query=&f_type=profile)

- [ProWein 2026 Exhibitor List – prowein.com](https://www.prowein.com/vis/v1/en/search?ticket=g_u_e_s_t&_query=&f_type=profile)

- [REHACARE 2025 Exhibitor List – rehacare.com](https://www.rehacare.com/vis/v1/en/search?ticket=g_u_e_s_t&_query=&f_type=profile)

- [TOP HAIR 2026 Exhibitor List – top-hair-international.com](https://www.top-hair-international.com/vis/v1/en/search?ticket=g_u_e_s_t&_query=&f_type=profile)

- [VALVE WORLD EXPO 2026 Exhibitor List – valveworldexpo.com](https://www.valveworldexpo.com/vis/v1/en/search?ticket=g_u_e_s_t&_query=&f_type=profile)

- [XPONENTIAL Europe 2026 Exhibitor List – xponential-europe.com](https://www.xponential-europe.com/vis/v1/en/search?ticket=g_u_e_s_t&_query=&f_type=profile)

- [wire Duesseldorf 2026 Exhibitor List – wire-tradefair.com](https://www.wire-tradefair.com/vis/v1/en/search?ticket=g_u_e_s_t&_query=&f_type=profile)

- [THERMPROCESS 2023 Exhibitor List – thermprocess-online.com](https://www.thermprocess-online.com/vis/v1/en/search?ticket=g_u_e_s_t&_query=&f_type=profile)

- [drupa 2024 Exhibitor List – drupa.com](https://www.drupa.com/vis/v1/en/search?ticket=g_u_e_s_t&_query=&f_type=profile)

- [Tube Duesseldorf 2026 Exhibitor List – tube-tradefair.com](https://www.tube-tradefair.com/vis/v1/en/search?ticket=g_u_e_s_t&_query=&f_type=profile)

---

## Testing Exhibitor List URLs for FREE

- Since I have multiple exhibitor list scraper actors for different types of trade event websites, it might be hard to find the correct actor for your exhibitor list URL.

- Use [**Exhibitor List Scrapers URL Tester**](https://apify.com/skython/exhibitor-list-scrapers-router) actor to test your exhibitor list URLs **for FREE** and see which scraper can process them.

---

## Exhibitor List Scraper - All-In-One Version

- I also provide an **All-In-One** version that combines **my 30+ exhibitor list scrapers** into a single actor.

- Instead of searching for the correct scraper for each event URL, simply provide the event URL and the actor automatically selects the appropriate scraper.

- ➡️ [Exhibitor List Scraper - All-In-One](https://apify.com/skython/exhibitor-list-scraper)

---

## Data Fields

<table>
  <thead>
    <tr>
    <th><span style="font-size:14px;">Company</span></th>
    <th><span style="font-size:14px;">Social</span></th>
    <th><span style="font-size:14px;">Additional</span></th>
    </tr>
  </thead>
    <tbody>
        <tr>
            <td>Profile URL</td>
            <td>LinkedIn</td>
            <td>Hall Stands</td>
        </tr>
        <tr>
            <td>Company Name</td>
            <td>Facebook</td>
            <td>Product Categories</td>
        </tr>
        <tr>
            <td>Address</td>
            <td>Instagram</td>
            <td>Description</td>
        </tr>
        <tr>
            <td>Website</td>
            <td>Twitter / X</td>
            <td>Business Data</td>
        </tr>
        <tr>
            <td>Email</td>
            <td>YouTube</td>
            <td>Co-Exhibitors</td>
        </tr>
        <tr>
            <td>Phone</td>
            <td>TikTok</td>
            <td>Contact Persons</td>
        </tr>
    </tbody>
</table>

<br>

---

## Example Output

```json
{
  "___exhibitor_profile_url": "https://www.caravan-salon.com/vis/v1/en/exhprofiles/KW4iyr6YRYKEB9X68R4k1g",
  "__company_name": "Arnott Europe B.V.",
  "_company_address": "Industrieweg 19, Waalwijk, 5145 PD, Netherlands",
  "_company_country": "Netherlands",
  "_company_email": "info@arnotteurope.com",
  "_company_phone": "+31 73 7850580",
  "_company_website": "https://www.arnotteurope.com/",
  "_hall_stands": "Hall 13 / D32",
  "_social_url_linkedin": "https://www.linkedin.com/company/arnott-suspension-europe/",
  "_social_url_facebook": "https://www.facebook.com/ArnottSuspensionEU/",
  "_social_url_instagram": "https://www.instagram.com/arnottsuspension/",
  "_social_url_youtube": "https://www.youtube.com/@ArnottSuspension",
  "company_description": "The Trusted Strength of Air Helper Kits\nAnd Why Demand Keeps Growing...",
  "number_of_employees": "100-499",
  "foundation": "1989",
  "product_categories": [
    {
      "title": "Vehicle parts / Chassis units / Axles / Trailer equipment",
      "subcategories": [
        {
          "title": "Suspension systems / Parts",
          "subcategories": null
        }
      ]
    }
  ],
  "contact_persons": [
    {
      "__name": "Danny Brink",
      "_email": "danny.****@arnotteurope.com",
      "_phone": "+49 170 55 30 ***",
      "_position": "Business Development Manager",
      "linkedin": "https://www.linkedin.com/company/arnott-suspension-europe",
      "facebook": "https://www.facebook.com/ArnottSuspensionEU/",
      "instagram": "https://www.instagram.com/arnottsuspension",
      "youtube": "https://www.youtube.com/@ArnottSuspension"
    }
  ]
}
```

<br>

---

## My Other Exhibitor List Scrapers

- [Exhibitor List Scraper - All-In-One](https://apify.com/skython/exhibitor-list-scraper)

- [Koelnmesse Exhibitor List Scraper](https://apify.com/skython/koelnmesse-exhibitor-list-scraper)

- [Messe Frankfurt Exhibitor List Scraper](https://apify.com/skython/messe-frankfurt-exhibitor-list-scraper)

- [Map Your Show Exhibitor List Scraper](https://apify.com/skython/map-your-show-exhibitor-list-scraper)

- [Xporience Exhibitor List Scraper](https://apify.com/skython/xporience-exhibitor-list-scraper)

- [Reed Expo Exhibitor List Scraper](https://apify.com/skython/reed-expo-exhibitor-list-scraper)

- [Messe München Exhibitor List Scraper](https://apify.com/skython/messe-muenchen-exhibitor-list-scraper)

- [Xporience Exhibitor List Scraper V2](https://apify.com/skython/xporience-exhibitor-list-scraper-2)

- [Nürnberg Messe Exhibitor List Scraper](https://apify.com/skython/nuernberg-messe-exhibitor-list-scraper)

- [GSMA MWC Exhibitor List Scraper](https://apify.com/skython/gsma-mwc-exhibitor-list-scraper)

- [Messe Berlin Exhibitor List Scraper](https://apify.com/skython/messe-berlin-exhibitor-list-scraper)

- [AFAG Messe Exhibitor List Scraper](https://apify.com/skython/afag-messe-exhibitor-list-scraper)

- [Messe Stuttgart Exhibitor List Scraper](https://apify.com/skython/messe-stuttgart-exhibitor-list-scraper)

- [Messe Essen Exhibitor List Scraper](https://apify.com/skython/messe-essen-exhibitor-list-scraper)

- [Informa Markets Exhibitor List Scraper](https://apify.com/skython/informa-markets-exhibitor-list-scraper)

- [Informa Markets Exhibitor List Scraper V2](https://apify.com/skython/informa-markets-exhibitor-list-scraper-2)

- [Ungerboeck Exhibitor List Scraper](https://apify.com/skython/ungerboeck-exhibitor-list-scraper)

- [A2Z Events Exhibitor List Scraper](https://apify.com/skython/a2z-events-exhibitor-list-scraper)

- [Deutsche Messe Exhibitor List Scraper](https://apify.com/skython/deutsche-messe-exhibitor-list-scraper)

- [Newfront Exhibitor List Scraper](https://apify.com/skython/newfront-exhibitor-list-scraper)

- [Goeshow Exhibitor List Scraper](https://apify.com/skython/goeshow-exhibitor-list-scraper)

- [EasyFairs Exhibitor List Scraper](https://apify.com/skython/easyfairs-exhibitor-list-scraper)

- [IEG Expo Exhibitor List Scraper](https://apify.com/skython/ieg-expo-exhibitor-list-scraper)

- [The Smarter E Exhibitor List Scraper](https://apify.com/skython/the-smarter-e-exhibitor-list-scraper)

- [Schall Messen Exhibitor List Scraper](https://apify.com/skython/schall-messen-exhibitor-list-scraper)

- [Messe München Exhibitor List Scraper V2](https://apify.com/skython/messe-muenchen-exhibitor-list-scraper-2)

- [Comexposium Exhibitor List Scraper](https://apify.com/skython/comexposium-exhibitor-list-scraper)

- [IME Events Exhibitor List Scraper](https://apify.com/skython/ime-events-exhibitor-list-scraper)

- [ANDMORE Exhibitor List Scraper](https://apify.com/skython/andmore-exhibitor-list-scraper)

- [Comexposium Exhibitor List Scraper V2](https://apify.com/skython/comexposium-exhibitor-list-scraper-2)