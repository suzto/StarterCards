# Standard Video

## Summary

The <b>Standard Video Card</b> prioritizes brevity without sacrificing functionality. Whether you’re after tech insights or artistic inspiration, this card delivers. Discover additional choices—bookmark, share, or dive into more content—from the overflow menu.

_user-sent_ card example:

![picture of the extension in action](assets/videoCard.png)

## Compatibility

![Adaptive Card Version](https://img.shields.io/badge/Adaptive%20Card%20Version-1.5-green.svg)

## Solution

Solution|Author(s)
--------|---------
Course Video | <a href="https://github.com/SuzanneTocco"><img align="center" width="28" height="28" src="https://wsrv.nl/?url=https://avatars.githubusercontent.com/u/149005128?v=4&w=36&h=36&fit=cover&mask=circle"></a> &nbsp; [Suz Tocco](https://github.com/SuzanneTocco) &nbsp;<a href="https://github.com/pabloas-ms"><img align="center" width="28" height="28" src="https://wsrv.nl/?url=https://avatars.githubusercontent.com/u/160079710?v=4&w=36&h=36&fit=cover&mask=circle"></a> &nbsp; [Pablo Vicente Astudillo Quintero](https://github.com/pabloas-ms) | Microsoft  

## Version history

Version|Date|Comments
-------|----|--------
1.0| April 11, 2024 | Initial release

### Disclaimer

***THIS CODE IS PROVIDED _AS IS_ WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.***

## Responsive Layouts

This card utilizes our responsive framework, allowing for multiple layouts or content modifications for specific set width ranges. For more details on coding with this framework, see <a href="https://learn.microsoft.com/en-us/microsoftteams/platform/task-modules-and-cards/cards/cards-format?tabs=adaptive-md%2Cdesktop%2Cconnector-html#adaptive-card-responsive-layout">Design responsive Adaptive Cards</a>.

![to be added](assets/card-layouts.png)

## Inspiration Gallery

Below you'll find a few alternative expressions of the card.

![TBD](assets/inspiration.png)
<br/><br/>

## 1) 👩‍🎨 Personalize This Card

### Step-by-step instructions and tips

#### 1) Copy the card JSON into the Designer Tool

This tool is <b>supported by Teams</b> for building and editing cards. Copy the card payload below and paste into the Designer tool.

> [!NOTE]
> Responsive layout is not supported in the Designer.

<!--- dropdown --->

<details closed>
<summary>
Click to see the card payload
</summary>

```json

          
{
  "type": "AdaptiveCard",
  "speak": "Web development bootcamp video",
  "$schema": "http://adaptivecards.io/schemas/adaptive-card.json",
  "version": "1.5",
  "body": [
    {
      "type": "Image",
      "url": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/standard-video/assets/video_image.png",
      "altText": "Web Development Bootcamp Video"
    },
    {
      "type": "TextBlock",
      "text": "Web Development Bootcamp",
      "wrap": true,
      "size": "Large",
      "weight": "Bolder"
    },
    {
      "type": "TextBlock",
      "text": "HackLab Films",
      "wrap": true,
      "spacing": "Small",
      "weight": "Bolder"
    },
    {
      "type": "TextBlock",
      "text": "24m · 17.1M views · 2 months ago",
      "wrap": true,
      "spacing": "None"
    },
    {
      "type": "ActionSet",
      "targetWidth": "atLeast:narrow",
      "actions": [
        {
          "type": "Action.OpenUrl",
          "title": "Open",
          "url": "https://adaptivecards.io/"
        },
        {
          "type": "Action.OpenUrl",
          "title": "Add to calendar",
          "url": "https://adaptivecards.io/",
          "iconUrl": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/standard-video/assets/add_to_calendar_icon.png"
        },
        {
          "type": "Action.OpenUrl",
          "title": "Share in Teams",
          "mode": "secondary",
          "url": "https://adaptivecards.io/",
          "iconUrl": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/standard-video/assets/menu_icon_teams.png"
        },
        {
          "type": "Action.OpenUrl",
          "title": "Download",
          "url": "https://adaptivecards.io/",
          "mode": "secondary",
          "iconUrl": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/standard-video/assets/menu_icon_download.png"
        },
        {
          "type": "Action.OpenUrl",
          "title": "Copy link",
          "mode": "secondary",
          "url": "https://adaptivecards.io/",
          "iconUrl": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/standard-video/assets/menu_icon_link.png"
        }
      ]
    },
    {
      "type": "ActionSet",
      "targetWidth": "veryNarrow",
      "actions": [
        {
          "type": "Action.OpenUrl",
          "title": "Open",
          "url": "https://adaptivecards.io/"
        },
        {
          "type": "Action.OpenUrl",
          "iconUrl": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/standard-video/assets/add_to_calendar_icon.png",
          "url": "https://adaptivecards.io/"
        },
        {
          "type": "Action.OpenUrl",
          "iconUrl": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/standard-video/assets/menu_icon_teams.png",
          "title": "Share in Teams",
          "mode": "secondary",
          "url": "https://adaptivecards.io/"
        },
        {
          "type": "Action.OpenUrl",
          "iconUrl": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/standard-video/assets/menu_icon_download.png",
          "title": "Download",
          "url": "https://adaptivecards.io/",
          "mode": "secondary"
        },
        {
          "type": "Action.OpenUrl",
          "iconUrl": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/standard-video/assets/menu_icon_link.png",
          "title": "Copy link",
          "mode": "secondary",
          "url": "https://adaptivecards.io/"
        }
      ]
    }
  ]
}

```

</details>

*To create a "full width" card, add the following code to the JSON.* <br>

```json
"msTeams": {
    "width": "full"
  },
```

<a href="https://adaptivecards.io/designer?card=https%3A%2F%2Fraw.githubusercontent.com%2Fsuzto%2FStarterCards%2Fmain%2Fsamples%2Fstandard-video%2Fcard.json" target="_blank">
  <img src="../../assets/open_designer_button.png" width="190" alt="Open in Adaptive Card Designer" />
</a>

#### 2) Replace the Hero Image

If you’re creating an image, use a 16:9 aspect ratio. Save the image as a transparent PNG at 2x size to ensure good resolution across endpoints.

* For YouTube, Vimeo, and DailyMotion Inline Media Cards, the “play” button will not need to be added.
* Update the image URL to link to your desired image and specify the URL for the selection action.
* <b>Note:</b> A radius feature for adding rounded corners to the image is coming soon. In the meantime, you can manually add a 6px radius to the corners.

#### 3) Update the Video Information

Modify the details or statistics as desired.

#### 4) Update Button Copy and Actions

Customize button text and add or remove actions to suit your needs. <br>
For icons, use the color #818181 to ensure readability in light/dark modes. Icons should fit edge-to-edge in a 16x16 square. Save them as transparent PNGs at 2x size for good resolution across endpoints. Access Fluent icon asset links in the [Resources section](#resources--tools) on this page.

<br>

***For further design modifications** use the Microsoft Teams UI Kit in Figma to create, visualize, spec <a href="assets/video_spec.png">(see current card spec)</a> , and verify the layouts before coding.<br />

<a href="https://www.figma.com/community/file/916836509871353159">
<img src="../../assets/teams_ui_kit_button.png" width="172" alt="Get the Microsoft Teams UI Kit" />
</a>

<br>

## 2) 🚗 Test Your Card

This is where the rubber meets the road to ensure high quality cards for all users across all endpoints. Road test your cards considering the following:

* <b>Themes:</b> Light Mode, Dark Mode, High Contrast
* <b>Common widths:</b> Chat, Channel, Meeting Chat, Phone (iOS- Portrait/landscape, Android-Portrait/landscape), Tablet (iOS- Portrait/landscape, Android-Portrait/landscape)
* <b>Accessibility:</b> Color contrast if creating new visuals, tabbing with keyboard or mobile equivelents, Voice assistance (readers to read card content)

<br>

## Resources & Tools ##

* **Learn**: For complete details on how to design and build adaptive cards for your Teams app, visit the Microsoft Teams Learn website pages on  [Design Adaptive Cards for Your Teams App](https://learn.microsoft.com/en-us/microsoftteams/platform/task-modules-and-cards/cards/design-effective-cards?tabs=design) and [Build Cards](https://learn.microsoft.com/en-us/microsoftteams/platform/task-modules-and-cards/what-are-cards) (You can use the [schema explorer](https://adaptivecards.io/explorer/) to learn about the structure and options of each element.

* **Design**: Our tools can help you learn Teams patterns and design apps and cards.

  * Design Teams apps and cards with the [The Microsoft Teams UI Kit](https://www.figma.com/community/file/916836509871353159), which has core components, templates, and best practices.
  * Find Microsoft icons from [IconCloud](https://iconcloud.design/browse/Fluent%20System%20Library/Fluent%20Regular) or the [Fluent 2 Iconography site](https://fluent2.microsoft.design/iconography) and modify them to to use in your cards (you'll need to save them out as pngs while we work on building in Fluent icon support).

* **Build**: Edit, build, preview, and test cards with our Teams Development Portal [Adaptive Card Designer](https://dev.teams.microsoft.com/cards).

</p>

## Contribute ##

Refer to the [contribution docs](/CONTRIBUTE.md) for more information.

## Help

We do not support samples, but we this community is always willing to help, and we want to improve these samples. We use GitHub to track issues, which makes it easy for  community members to volunteer their time and help resolve issues.

You can try looking at [issues related to this sample](https://github.com/pnp/AdaptiveCards-Templates/issues) to see if anybody else is having the same issues.
