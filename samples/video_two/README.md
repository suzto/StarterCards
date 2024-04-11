# Course Video

## Summary

This versatile and robust card serves as a learning hub for video content. Tailor it to your specific needs, whether it’s a series of courses, tutorials, or informative clips. Customize titles, descriptions, and author information to create engaging viewing experiences.

_bot-sent_ card example:

![picture of the extension in action](assets/hero.png)



## Compatibility

![Adaptive Card Version](https://img.shields.io/badge/Adaptive%20Card%20Version-1.5-green.svg)


## Solution

Solution|Author(s)
--------|---------
Course Video | <a href="https://github.com/SuzanneTocco"><img align="center" width="28" height="28" src="https://wsrv.nl/?url=https://avatars.githubusercontent.com/u/149005128?v=4&w=36&h=36&fit=cover&mask=circle"> </a> &nbsp; [Suz Tocco](https://github.com/SuzanneTocco) &nbsp; <a href="https://github.com/pabloas-ms"><img align="center" width="28" height="28" src="https://wsrv.nl/?url=https://avatars.githubusercontent.com/u/160079710?v=4&w=36&h=36&fit=cover&mask=circle"></a> &nbsp; [Pablo Vicente Astudillo Quintero](https://github.com/pabloas-ms) | Microsoft  


## Version history

Version|Date|Comments
-------|----|--------
1.0| April 11, 2024 | Initial release


#### Disclaimer
***THIS CODE IS PROVIDED *AS IS* WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.***


## Design Layouts

This card utilizes our responsive framework, creating multiple layouts or content modifications for specific width ranges. For more details on coding with this framework, see insert msft learn link.

![picture of the extension in action](assets/layouts.png)

## Inspiration Gallery

lorem ipsum delor amet consectuer leoeian

![picture of alterations](assets/video_variations.png) 
<br/><br/>



## 1) 👩‍🎨 Personalize This Card 




### Step by step instructions and tips: 

  
 #### 1) Open in the Microsoft Teams Designer Editing tool
 This is our ___Teams supported___ tool for building and editing cards.
 
 <a href="https://dev.teams.microsoft.com/home">
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


__Need more complex design changes?__ Use the Microsoft Teams UI Kit to modify or build on this design <a href="assets/video_spec.png">(detailed spec)</a> and verify the layouts before coding.<br />

<a href="https://www.figma.com/community/file/916836509871353159">
<img src="/assets/teams_ui_kit_button.png" width="172" alt="Get the Microsoft Teams UI Kit" />
</a> 



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
````
