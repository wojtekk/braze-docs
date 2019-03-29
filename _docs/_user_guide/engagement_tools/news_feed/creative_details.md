---
nav_title: Creating a News Feed Item
page_order: 3.1
---

# News Feed Card Specifications

## News Feed Cards

![Classic Card][2]

Standard news feed cards consist of:

- 110x110 image
- Title
- Body Text
- Link (In-App/Web)

## Captioned Image Cards

![Captioned Image][3]

Captioned Image cards consist of:

- 600x450 image
- Title
- Body Text
- Link (In-App/Web)

## Banner Cards

![NewsFeedBanner][4]

Banner cards consist of:

- 600x100 image
- Link (In-App/Web)

## Cross Promotions Cards

![CrossPromo][5]

Cross promotion cards allow you to showcase another app that's in the app store. Note that you may not advertise apps which are the property of companies other than your own.


# Image guidelines

|          Card type         |          Aspect Ratio         | Recommended Image Size | Maximum Image Size |   File Types  |
|:-----------------------------:|:----------------------:|:------------------:|:-------------:|
|          Classic         | 1:1 (110 pixels wide minimum) |          500KB         |         1MB        | PNG, JPG, GIF |
|          Captioned image         | 4:3 (600 pixels wide minimum) |          500KB         |         1MB        | PNG, JPG, GIF |
|          Banner         | 6:1 (600 pixels wide minimum) |          500KB         |         1MB        | PNG, JPG, GIF |

- PNG files are recommended.
- A custom image loading library is required in order to display Gifs on Android. We recommend Glide.
- Smaller, high quality images will load faster, so it’s recommended to use the smallest asset possible to achieve your desired output.

[1]: {% image_buster /assets/img_archive/newsfeed1_new.png %}
[2]: {% image_buster /assets/img_archive/classiccard.png %}
[3]: {% image_buster /assets/img_archive/captionedimage.png %}
[4]: {% image_buster /assets/img_archive/newsfeedbanner.png %}
[5]: {% image_buster /assets/img_archive/crosspromo.png %}
[6]: {% image_buster /assets/img_archive/news-feed-title-summary_new.png %}
[7]: {{ site.baseurl }}/developer_guide/platform_integration_guides/ios/advanced_use_cases/linking/#deep-linking-to-app-settings
[8]: {% image_buster /assets/img_archive/newsfeed2_new.png %}
[9]: {% image_buster /assets/img_archive/newsfeedinapp.gif %}
[10]: {{ site.baseurl }}/user_guide/engagement_tools/segments/creating_a_segment/#creating-a-segment
[11]: {% image_buster /assets/img_archive/targetsegment_new.png %}
[12]: {% image_buster /assets/img_archive/newsfeedpreview_new.png %}
[13]: {{ site.baseurl }}/help/best_practices/client_integration_gallery/#client-integration-newsfeed
[14]: {% image_buster /assets/img_archive/linked-in-app_new.png %}
