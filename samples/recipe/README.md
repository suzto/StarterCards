# Recipe
notes: hide ui kit and move designer to bottom <br/>
remove any action that we don't support (share)<br/>
info on see more see less<br/>
don't show schema<br/>
remove designer icon set (ask viva how they implemented )<br/>
See how to put images in public place to test (onedrive?)
figure out if there is a way to view a card sent from dev portal in meeting chat
image in container, check radius


## Summary

This card features a single recipe with an eye-catching image. The basic facts and a summary snippet (that can be expanded) give more details about the recipe. The card may also have simple actions like view, add to cart, or share.


`example of card sent in chat`


![picture of the extension in action](assets/card.png)

 
## Compatibility

![Adaptive Card Version](https://img.shields.io/badge/Adaptive%20Card%20Version-xx-green.svg)



## Solution

Solution|Author(s)
--------|---------
recipe | <a href="https://github.com/SuzanneTocco"><img align="center" width="32" height="32" src="https://wsrv.nl/?url=https://avatars.githubusercontent.com/u/149005128?v=4&w=36&h=36&fit=cover&mask=circle"></a> &nbsp; [Suz Tocco](https://github.com/SuzanneTocco) \| Microsoft  

 
## Version history

Version|Date|Comments
-------|----|--------
1.0| October 31, 2023 | Initial release


## Disclaimer
**THIS CODE IS PROVIDED *AS IS* WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**


## Personalization Examples

For inspiration, check out these examples of card content and actions. The card will adjust to different screen sizes, so make sure it works well on all of them!

![picture of alterations](assets/card_variations.png)


## 1) 👩‍🎨 Personalize This Card 

We designed this card for Teams app partners who need to support your use case. This card type has a unique visual and interaction pattern to ensure a consistent user experience. To make this card suit your needs, simply adjust the text, images, and actions.

__To modify or extend this card__ <a href="assets/design_spec.png">(design spec)</a>, use the Microsoft Teams UI Kit to fine tune your design before coding.<br />

<a href="https://www.figma.com/community/file/916836509871353159">
<img src="/assets/teams_ui_kit_button.png" width="172" alt="Get the Microsoft Teams UI Kit" />
</a> 


### Step by step instructions and tips: 

  
 #### 1) Open in the Microsoft Teams Designer Editing tool
 This is our ___Teams supported___ tool for building and editing cards.
 
 <a href="https://adaptivecards.io/designer/index.html?card=https%3A%2F%2Fraw.githubusercontent.com%2Fpnp%2FAdaptiveCards-Templates%2Fmain%2Fsamples%2Femployee-onboarding%2Fac-qv-employee-onboarding.json&data=https%3A%2F%2Fraw.githubusercontent.com%2Fpnp%2FAdaptiveCards-Templates%2Fmain%2Fsamples%2Femployee-onboarding%2Fac-qv-employee-onboarding.data.json">
        <img src="/assets/open_designer_button.png" width="190" alt="Open in Adaptive Card Designer" />
    </a>
  

#### 2) Replace the image
 Instructions on how to do that go in this space here. Can use sentence or bulletpoints or expand/collapse section


<!--- dropdown --->

<details closed>
<summary>
 Photo and image resources
</summary> <br />

<p>One- Instructions go here about free images</p>
</details>

<!--- dropdown --->

<details closed>
<summary>
 Advanced image editing information
</summary> <br />

<p>One- Instructions go here</p>

</details>  


#### 3) Update the copy and set truncation
 Instructions on how to do that go in this space here. Can use sentence or bulletpoints or expand/collapse section

#### 4) Next steps goes here
 Instructions on how to do that go in this space here. Can use sentence or bulletpoints or expand/collapse section

<p>&nbsp;</p>


## 2) 🚗 Test Drive Your Card
ADD REAL EXAMPLES FROM RENDERINGS (DESKTOP, iOS, MEETING CHAT)

Visit our <a href="/TESTDRIVEYOURCARD.md">Test Drive Your Card</a> page to learn how to preview your card on various Teams surfaces/endpoints and color modes.

![picture of size examples](/assets/endpoint_size_example.png)

_After you've fully tested your card, <a href="https://learn.microsoft.com/en-us/microsoftteams/platform/concepts/deploy-and-publish/appsource/prepare/submission-checklist?tabs=desktop#compile-testing-instructions">submit it to the Teams Store</a> for publishing and get ready to launch! 🚀_

<p>&nbsp;</p>


## Resources & Tools: ##
 

- __Learn__: For complete details on how to design and build adaptive cards for your Teams app, visit the Microsoft Teams Learn website pages on  [Design Adaptive Cards for Your Teams App](https://learn.microsoft.com/en-us/microsoftteams/platform/task-modules-and-cards/cards/design-effective-cards?tabs=design) and [Build Cards](https://learn.microsoft.com/en-us/microsoftteams/platform/task-modules-and-cards/what-are-cards) (You can use the [schema explorer](https://adaptivecards.io/explorer/) to learn about the structure and options of each element.


- __Design__: Our tools can help you learn Teams patterns and design apps and cards.

  - Design Teams apps and cards with the [The Microsoft Teams UI Kit](https://www.figma.com/community/file/916836509871353159), which has core components, templates, and best practices.
  - Find Microsoft icons from [IconCloud](https://iconcloud.design/browse/Fluent%20System%20Library/Fluent%20Regular) or the [Fluent 2 Iconography site](https://fluent2.microsoft.design/iconography) and use them in your cards. You can also use the [Card Designer Icon Set](https://learn.microsoft.com/en-us/sharepoint/dev/spfx/viva/get-started/fluent-icons-limitations#card-designer-icons-set) which is fully supported.


- __Build__: Edit, build, preview, and test cards with our Teams Development Portal [Adaptive Card Designer](https://dev.teams.microsoft.com/cards).
    
</p>


## Contribute: ##
Refer to the [contribution docs](/CONTRIBUTE.md) for more information.  


## Help

Samples are not supported, but this community is helpful and we want to make the samples better. We track issues on GitHub, which lets community members contribute their time and skills to solve them.

A possible way to check if others have the same issues is to look at the [issues related to this sample](https://github.com/OfficeDev/Microsoft-Teams-Card-Samples/issues).


### Card payload

````
{
  "type": "AdaptiveCard",
  "$schema": "http://adaptivecards.io/schemas/adaptive-card.json",
  "version": "1.5",
  "body": [
    {
      "type": "Image",
      "altText": "Image of Apricot-Chile Glazed Chicken",
      "size": "Stretch",
      "url": "https://onedrive.live.com/embed?resid=EBE108865B49234E%21142072&authkey=%21AIH0yXnxgH5RoCY&width=840&height=360"
    },
    {
      "type": "TextBlock",
      "text": "Apricot-Chile Glazed Chicken",
      "wrap": true,
      "size": "Large",
      "weight": "Bolder",
      "color": "Default"
    },
    {
      "type": "TextBlock",
      "text": "15 min · 215 calories · 29g protein",
      "wrap": true,
      "spacing": "None",
      "fontType": "Default",
      "size": "Small",
      "weight": "Default",
      "isSubtle": true,
      "color": "Default"
    },
    {
      "type": "TextBlock",
      "id": "truncatedText",
      "text": "This sweet apricot-chile glazed broccoli recipe marries fruit and chiles to make this dish mouthwateringly special. Use organic jam in place of preserves for a smoother, prettier glaze if you are into spicy food, then this will be right up your alley.\n\nThe recipe calls for 1/4 cup of the chili sauce which gives the chicken quite a bite on the palate. But for all you heat lovers, it's definitely a good feel.",
      "wrap": true,
      "maxLines": 3
    },
    {
      "type": "TextBlock",
      "id": "fullText1",
      "text": "This sweet apricot-chile glazed broccoli recipe marries fruit and chiles to make this dish mouthwateringly special. Use organic jam in place of preserves for a smoother, prettier glaze if you are into spicy food, then this will be right up your alley.",
      "wrap": true,
      "isVisible": false
    },
    {
      "type": "TextBlock",
      "id": "fullText2",
      "text": "The recipe calls for 1/4 cup of the chili sauce which gives the chicken quite a bite on the palate. But for all you heat lovers, it's definitely a good feel.",
      "wrap": true,
      "isVisible": false
    },
    {
      "type": "RichTextBlock",
      "id": "showMore",
      "targetWidth": "atLeast:narrow",
      "inlines": [
        {
          "type": "TextRun",
          "text": "Show more",
          "selectAction": {
            "type": "Action.ToggleVisibility",
            "targetElements": [
              "truncatedText",
              "fullText1",
              "fullText2",
              "showMore",
              "showLess"
            ]
          }
        }
      ]
    },
    {
      "type": "RichTextBlock",
      "id": "showLess",
      "targetWidth": "atLeast:narrow",
      "inlines": [
        {
          "type": "TextRun",
          "text": "Show less",
          "selectAction": {
            "type": "Action.ToggleVisibility",
            "targetElements": [
              "truncatedText",
              "fullText1",
              "fullText2",
              "showMore",
              "showLess"
            ]
          }
        }
      ],
      "isVisible": false
    },
    {
      "type": "ActionSet",
      "targetWidth": "atLeast:narrow",
      "actions": [
        {
          "type": "Action.OpenUrl",
          "title": "View recipe",
          "url": "https://www.tasteofhome.com/recipes/spicy-apricot-glazed-chicken/"
        },
        {
          "type": "Action.Submit",
          "title": "Add to cart",
          "iconUrl": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/recipe/assets/cart_icon.png"
        }
      ],
      "spacing": "Medium"
    },
    {
      "type": "ActionSet",
      "targetWidth": "veryNarrow",
      "actions": [
        {
          "type": "Action.OpenUrl",
          "title": "View recipe",
          "url": "https://www.tasteofhome.com/recipes/spicy-apricot-glazed-chicken/"
        },
        {
          "type": "Action.Submit",
          "iconUrl": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/recipe/assets/cart_icon.png"
        }
      ],
      "spacing": "Medium"
    }
  ]
}
````

### Full width Card payload

````
{
  "type": "AdaptiveCard",
  "msTeams": {
    "width": "full"
  },
  "$schema": "http://adaptivecards.io/schemas/adaptive-card.json",
  "version": "1.5",
  "body": [
    {
      "type": "Image",
      "altText": "Image of Apricot-Chile Glazed Chicken",
      "size": "Stretch",
      "url": "https://onedrive.live.com/embed?resid=EBE108865B49234E%21142072&authkey=%21AIH0yXnxgH5RoCY&width=840&height=360"
    },
    {
      "type": "TextBlock",
      "text": "Apricot-Chile Glazed Chicken",
      "wrap": true,
      "size": "Large",
      "weight": "Bolder",
      "color": "Default"
    },
    {
      "type": "TextBlock",
      "text": "15 min · 215 calories · 29g protein",
      "wrap": true,
      "spacing": "None",
      "fontType": "Default",
      "size": "Small",
      "weight": "Default",
      "isSubtle": true,
      "color": "Default"
    },
    {
      "type": "TextBlock",
      "id": "truncatedText",
      "text": "This sweet apricot-chile glazed broccoli recipe marries fruit and chiles to make this dish mouthwateringly special. Use organic jam in place of preserves for a smoother, prettier glaze if you are into spicy food, then this will be right up your alley.\n\nThe recipe calls for 1/4 cup of the chili sauce which gives the chicken quite a bite on the palate. But for all you heat lovers, it's definitely a good feel.",
      "wrap": true,
      "maxLines": 3
    },
    {
      "type": "TextBlock",
      "id": "fullText1",
      "text": "This sweet apricot-chile glazed broccoli recipe marries fruit and chiles to make this dish mouthwateringly special. Use organic jam in place of preserves for a smoother, prettier glaze if you are into spicy food, then this will be right up your alley.",
      "wrap": true,
      "isVisible": false
    },
    {
      "type": "TextBlock",
      "id": "fullText2",
      "text": "The recipe calls for 1/4 cup of the chili sauce which gives the chicken quite a bite on the palate. But for all you heat lovers, it's definitely a good feel.",
      "wrap": true,
      "isVisible": false
    },
    {
      "type": "RichTextBlock",
      "id": "showMore",
      "targetWidth": "atLeast:narrow",
      "inlines": [
        {
          "type": "TextRun",
          "text": "Show more",
          "selectAction": {
            "type": "Action.ToggleVisibility",
            "targetElements": [
              "truncatedText",
              "fullText1",
              "fullText2",
              "showMore",
              "showLess"
            ]
          }
        }
      ]
    },
    {
      "type": "RichTextBlock",
      "id": "showLess",
      "targetWidth": "atLeast:narrow",
      "inlines": [
        {
          "type": "TextRun",
          "text": "Show less",
          "selectAction": {
            "type": "Action.ToggleVisibility",
            "targetElements": [
              "truncatedText",
              "fullText1",
              "fullText2",
              "showMore",
              "showLess"
            ]
          }
        }
      ],
      "isVisible": false
    },
    {
      "type": "ActionSet",
      "targetWidth": "atLeast:narrow",
      "actions": [
        {
          "type": "Action.OpenUrl",
          "title": "View recipe",
          "url": "https://www.tasteofhome.com/recipes/spicy-apricot-glazed-chicken/"
        },
        {
          "type": "Action.Submit",
          "title": "Add to cart",
          "iconUrl": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/recipe/assets/cart_icon.png"
        }
      ],
      "spacing": "Medium"
    },
    {
      "type": "ActionSet",
      "targetWidth": "veryNarrow",
      "actions": [
        {
          "type": "Action.OpenUrl",
          "title": "View recipe",
          "url": "https://www.tasteofhome.com/recipes/spicy-apricot-glazed-chicken/"
        },
        {
          "type": "Action.Submit",
          "iconUrl": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/recipe/assets/cart_icon.png"
        }
      ],
      "spacing": "Medium"
    }
  ]
}
````