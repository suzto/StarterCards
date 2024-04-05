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
        "url": "https://adaptivecards.io/"
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
          "items": [
            {
              "type": "Rating",
              "value": "4",
              "color": "Marigold"
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
              "url": "https://github.com/suzto/StarterCards/blob/main/samples/video_two/assets/logo_image.png?raw=true",
              "width": "16px",
              "height": "16px"
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
      "spacing": "Small"
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