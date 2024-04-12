# Course Video

## Summary
The <b>Course Video Card</b> is a versatile and robust component designed to serve as a centralized learning hub for video content. Whether you’re offering a series of courses, tutorials, or informative clips, this card can be tailored to your specific needs. Customize titles, descriptions, and author information to create engaging viewing experiences.

_bot-sent_ card example:

![picture of the extension in action](assets/hero.png)



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


#### Disclaimer
***THIS CODE IS PROVIDED *AS IS* WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.***


## Responsive Layouts

This card utilizes our responsive framework, allowing for multiple layouts or content modifications for specific set width ranges. For more details on coding with this framework, see insert msft learn link.

![picture of the extension in action](assets/layouts.png)

## Inspiration Gallery

lorem ipsum delor amet consectuer leoeian

![picture of alterations](assets/video_variations.png) 
<br/><br/>



## 1) 👩‍🎨 Personalize This Card 


### Step-by-step instructions and tips: 

  
 #### 1) Open the Microsoft Teams Designer Editing tool
This tool is <b>supported by Teams</b> for building and editing cards. <b>Copy in the [JSON payload](#card-payload)</b> provided at the bottom of this page. Open in Adaptive Card Designer.
 
 <a href="https://dev.teams.microsoft.com/home">
        <img src="/assets/open_designer_button.png" width="190" alt="Open in Adaptive Card Designer" />
    </a>
  

#### 2) Replace the hero image
If you are creating an image use a 16:9 aspect ratio. I find saving out the image as a transparent png at 2x size ensures a good resolution across endpoints.
* Add "play_button.png" in assets folder if possible on top of your image.<br>
*For YouTube, Vimeo, and DailyMotion Inline Media Cards the "play" button will not need to be added.*
* Update the image url to link to your desired image as well as the URL for the selection action. <br>


*<b>Note:</b> We have a radius feature coming soon that will allow you to add a rounded corner to your image. In the meantime if you'd like to do this, please add a 6px radius to the corners.* <br>

#### 3) Replace the author/company logo
Replace the mini 16x16px square image. If you are creating a new image save it out as a transparent png at 2x size (to ensure good resolution) but keep the 16x16 fixed width in the card. 


#### 4) Update the description copy and set truncation
Set the maximum line truncation as desired. The "Show more" /  "Show less" feature can be kept or removed as desired.

#### 5) Update button copy and actions
* Update button text and actions to suit your needs. <br>
* <b>Creating icons:</b> If you'd like to add icons, the color should be #818181 to ensure readability on light/dark modes and should fit edge to edge in a 16x16 square. Save out the image as a transparent png at 2x size to ensure good resolution across endpoints. Access Fluent icon asset links in the [Resources section](#resources--tools) on this page.

<br>

__*For further design modifications__ use the Microsoft Teams UI Kit in Figma to create, visualize, spec <a href="assets/video_spec.png">(detailed spec)</a> , and verify the layouts before coding.<br />

<a href="https://www.figma.com/community/file/916836509871353159">
<img src="/assets/teams_ui_kit_button.png" width="172" alt="Get the Microsoft Teams UI Kit" />
</a> 

<br>

## 2) 🚗 Test your card

This is where the rubber meets the road to ensure high quality cards for all users across all endpoints. Road test your cards considering the following:
* <b>Themes:</b> Light Mode, Dark Mode, High Contrast
* <b>Common widths:</b> Chat, Channel, Meeting Chat, Phone (iOS- Portrait/landscape, Android-Portrait/landscape), Tablet (iOS- Portrait/landscape, Android-Portrait/landscape)
* <b>Accessibility:</b> Color contrast if creating new visuals, tabbing with keyboard or mobile equivelents, Voice assistance (readers to read card content)

  
<br>




## Resources & Tools ##
 

- __Learn__: For complete details on how to design and build adaptive cards for your Teams app, visit the Microsoft Teams Learn website pages on  [Design Adaptive Cards for Your Teams App](https://learn.microsoft.com/en-us/microsoftteams/platform/task-modules-and-cards/cards/design-effective-cards?tabs=design) and [Build Cards](https://learn.microsoft.com/en-us/microsoftteams/platform/task-modules-and-cards/what-are-cards) (You can use the [schema explorer](https://adaptivecards.io/explorer/) to learn about the structure and options of each element.


- __Design__: Our tools can help you learn Teams patterns and design apps and cards.

  - Design Teams apps and cards with the [The Microsoft Teams UI Kit](https://www.figma.com/community/file/916836509871353159), which has core components, templates, and best practices.
  - Find Microsoft icons from [IconCloud](https://iconcloud.design/browse/Fluent%20System%20Library/Fluent%20Regular) or the [Fluent 2 Iconography site](https://fluent2.microsoft.design/iconography) and modify them to to use in your cards (you'll need to save them out as pngs while we work on building in Fluent icon support). 


- __Build__: Edit, build, preview, and test cards with our Teams Development Portal [Adaptive Card Designer](https://dev.teams.microsoft.com/cards).
    
</p>


## Contribute ##
Refer to the [contribution docs](/CONTRIBUTE.md) for more information.


## Help

We do not support samples, but we this community is always willing to help, and we want to improve these samples. We use GitHub to track issues, which makes it easy for  community members to volunteer their time and help resolve issues.

You can try looking at [issues related to this sample](https://github.com/pnp/AdaptiveCards-Templates/issues) to see if anybody else is having the same issues.
<br><br>


***


### Card Payload

````
{
  "type": "AdaptiveCard",
  "$schema": "http://adaptivecards.io/schemas/adaptive-card.json",
  "version": "1.5",
  "body": [
    {
      "type": "Image",
      "url": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/video_two/assets/video_image.png",
      "selectAction": {
        "type": "Action.OpenUrl",
        "url": "https://adaptivecards.io/",
        "altText": "Intro to Graphic Design: Concepts Video"
      }
    },
    {
      "type": "TextBlock",
      "text": "Intro to Graphic Design: Concepts",
      "wrap": true,
      "size": "Large",
      "weight": "Bolder"
    },
    {
      "type": "ColumnSet",
      "columns": [
        {
          "type": "Column",
          "width": "auto",
          "verticalContentAlignment": "Center",
          "items": [
            {
              "type": "Rating",
              "value": "4",
              "color": "Marigold",
              "size": "Medium",
              "fallback": {
                "type": "TextBlock",
                "text": "4 Stars"
              }
            }
          ]
        },
        {
          "type": "Column",
          "width": "auto",
          "items": [
            {
              "type": "TextBlock",
              "text": "·"
            }
          ],
          "spacing": "Small"
        },
        {
          "type": "Column",
          "width": "auto",
          "items": [
            {
              "type": "TextBlock",
              "text": "1,160",
              "wrap": true
            }
          ],
          "spacing": "Small"
        }
      ],
      "spacing": "None"
    },
    {
      "type": "TextBlock",
      "text": "Course · 52m · Beginner",
      "wrap": true,
      "isSubtle": true,
      "spacing": "Small"
    },
    {
      "type": "ColumnSet",
      "columns": [
        {
          "type": "Column",
          "width": "auto",
          "items": [
            {
              "type": "Image",
              "url": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/video_two/assets/logo_image.png",
              "width": "16px",
              "height": "16px",
              "altText": "Logo"
            }
          ],
          "horizontalAlignment": "Center",
          "verticalContentAlignment": "Center"
        },
        {
          "type": "Column",
          "width": "auto",
          "items": [
            {
              "type": "TextBlock",
              "text": "Sketchpad Scholars",
              "wrap": true,
              "weight": "Bolder"
            }
          ],
          "spacing": "Small"
        },
        {
          "type": "Column",
          "targetWidth": "atLeast:narrow",
          "width": "auto",
          "items": [
            {
              "type": "TextBlock",
              "text": "·"
            }
          ],
          "spacing": "Small"
        },
        {
          "type": "Column",
          "targetWidth": "atLeast:narrow",
          "width": "auto",
          "items": [
            {
              "type": "TextBlock",
              "text": "Tony Harper",
              "wrap": true
            }
          ],
          "spacing": "Small"
        }
      ],
      "spacing": "None"
    },
    {
      "type": "TextBlock",
      "targetWidth": "atLeast:narrow",
      "text": "This course is designed to equip you with an understanding of the key principles and tools necessary for creating compelling designs. You'll gain practical experience with creative software and learn...",
      "wrap": true,
      "id": "truncatedText"
    },
    {
      "type": "TextBlock",
      "targetWidth": "atLeast:narrow",
      "text": "This course is designed to equip you with an understanding of the key principles and tools necessary for creating compelling designs. You'll gain practical experience with creative software and learn about design principles through hands-on projects that will help build your portfolio. Enroll now and start your journey to mastering the art of graphic design.",
      "wrap": true,
      "isVisible": false,
      "id": "fullText"
    },
    {
      "type": "RichTextBlock",
      "id": "showMore",
      "targetWidth": "atLeast:narrow",
      "spacing": "None",
      "inlines": [
        {
          "type": "TextRun",
          "text": "Show more",
          "selectAction": {
            "type": "Action.ToggleVisibility",
            "targetElements": [
              "truncatedText",
              "fullText",
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
      "spacing": "None",
      "inlines": [
        {
          "type": "TextRun",
          "text": "Show less",
          "selectAction": {
            "type": "Action.ToggleVisibility",
            "targetElements": [
              "truncatedText",
              "fullText",
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
          "title": "Open",
          "url": "https://adaptivecards.io/"
        },
        {
          "type": "Action.Execute",
          "title": "Bookmark",
          "iconUrl": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/video_two/assets/bookmark_icon.png"
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
          "type": "Action.Execute",
          "iconUrl": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/video_two/assets/bookmark_icon.png"
        }
      ]
    }
  ]
}
````

<!--  
### Full width Card Payload

````
{
  "type": "AdaptiveCard",
  "$schema": "http://adaptivecards.io/schemas/adaptive-card.json",
  "msTeams": {
    "width": "full
  }
  "version": "1.5",
  "body": [
    {
      "type": "Image",
      "url": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/video_two/assets/video_image.png",
      "selectAction": {
        "type": "Action.OpenUrl",
        "url": "https://adaptivecards.io/",
        "altText": "Intro to Graphic Design: Concepts Video"
      }
    },
    {
      "type": "TextBlock",
      "text": "Intro to Graphic Design: Concepts",
      "wrap": true,
      "size": "Large",
      "weight": "Bolder"
    },
    {
      "type": "ColumnSet",
      "columns": [
        {
          "type": "Column",
          "width": "auto",
          "verticalContentAlignment": "Center",
          "items": [
            {
              "type": "Rating",
              "value": "4",
              "color": "Marigold",
              "size": "Medium",
              "fallback": {
                "type": "TextBlock",
                "text": "4 Stars"
              }
            }
          ]
        },
        {
          "type": "Column",
          "width": "auto",
          "items": [
            {
              "type": "TextBlock",
              "text": "·"
            }
          ],
          "spacing": "Small"
        },
        {
          "type": "Column",
          "width": "auto",
          "items": [
            {
              "type": "TextBlock",
              "text": "1,160",
              "wrap": true
            }
          ],
          "spacing": "Small"
        }
      ],
      "spacing": "None"
    },
    {
      "type": "TextBlock",
      "text": "Course · 52m · Beginner",
      "wrap": true,
      "isSubtle": true,
      "spacing": "Small"
    },
    {
      "type": "ColumnSet",
      "columns": [
        {
          "type": "Column",
          "width": "auto",
          "items": [
            {
              "type": "Image",
              "url": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/video_two/assets/logo_image.png",
              "width": "16px",
              "height": "16px",
              "altText": "Logo"
            }
          ],
          "horizontalAlignment": "Center",
          "verticalContentAlignment": "Center"
        },
        {
          "type": "Column",
          "width": "auto",
          "items": [
            {
              "type": "TextBlock",
              "text": "Sketchpad Scholars",
              "wrap": true,
              "weight": "Bolder"
            }
          ],
          "spacing": "Small"
        },
        {
          "type": "Column",
          "targetWidth": "atLeast:narrow",
          "width": "auto",
          "items": [
            {
              "type": "TextBlock",
              "text": "·"
            }
          ],
          "spacing": "Small"
        },
        {
          "type": "Column",
          "targetWidth": "atLeast:narrow",
          "width": "auto",
          "items": [
            {
              "type": "TextBlock",
              "text": "Tony Harper",
              "wrap": true
            }
          ],
          "spacing": "Small"
        }
      ],
      "spacing": "None"
    },
    {
      "type": "TextBlock",
      "targetWidth": "atLeast:narrow",
      "text": "This course is designed to equip you with an understanding of the key principles and tools necessary for creating compelling designs. You'll gain practical experience with creative software and learn...",
      "wrap": true,
      "id": "truncatedText"
    },
    {
      "type": "TextBlock",
      "targetWidth": "atLeast:narrow",
      "text": "This course is designed to equip you with an understanding of the key principles and tools necessary for creating compelling designs. You'll gain practical experience with creative software and learn about design principles through hands-on projects that will help build your portfolio. Enroll now and start your journey to mastering the art of graphic design.",
      "wrap": true,
      "isVisible": false,
      "id": "fullText"
    },
    {
      "type": "RichTextBlock",
      "id": "showMore",
      "targetWidth": "atLeast:narrow",
      "spacing": "None",
      "inlines": [
        {
          "type": "TextRun",
          "text": "Show more",
          "selectAction": {
            "type": "Action.ToggleVisibility",
            "targetElements": [
              "truncatedText",
              "fullText",
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
      "spacing": "None",
      "inlines": [
        {
          "type": "TextRun",
          "text": "Show less",
          "selectAction": {
            "type": "Action.ToggleVisibility",
            "targetElements": [
              "truncatedText",
              "fullText",
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
          "title": "Open",
          "url": "https://adaptivecards.io/"
        },
        {
          "type": "Action.Execute",
          "title": "Bookmark",
          "iconUrl": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/video_two/assets/bookmark_icon.png"
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
          "type": "Action.Execute",
          "iconUrl": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/video_two/assets/bookmark_icon.png"
        }
      ]
    }
  ]
}
````  -->
