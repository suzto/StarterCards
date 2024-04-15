# Work Item

## Summary

The <b>Work Item Card</b> is your gateway to vibrant social connectivity. Ideal for broadcasting company updates, sharing posts, or fostering community ties, this card is versatile enough to match your messaging. Enrich it with custom text, imagery, and links for an immersive social journey.

_bot-sent_ card example:

![picture alt](assets/CommunicationsCard.png)










<a href="https://adaptivecards.io/designer?card=https%3A%2F%2Fraw.githubusercontent.com%2Fsuzto%2FStarterCards%2Fmain%2Fsamples%2Fwork_item%2Fcard.json"  target="_blank">
  <img src="../../assets/open_designer_button.png" width="190" alt="Open in Adaptive Card Designer" />
</a>

> [!NOTE]
> Responsive layout is not supported in the Designer.

### Card Payload

```json
{
  "type": "AdaptiveCard",
  "speak": "Bug 2837, icons not rendering in dark mode",
  "$schema": "http://adaptivecards.io/schemas/adaptive-card.json",
  "version": "1.5",
  "body": [
    {
      "type": "ColumnSet",
      "columns": [
        {
          "type": "Column",
          "width": "auto",
          "items": [
            {
              "type": "Image",
              "url": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/work_item/assets/thumb_image.png",
              "width": "56px",
              "height": "56px",
              "altText": "Logo"
            }
          ]
        },
        {
          "type": "Column",
          "width": "stretch",
          "items": [
            {
              "type": "TextBlock",
              "text": "Bug 2837 - Icons not rendering in dark mode",
              "wrap": true,
              "weight": "Bolder"
            },
            {
              "type": "ColumnSet",
              "targetWidth": "atLeast:narrow",
              "columns": [
                {
                  "type": "Column",
                  "width": "auto",
                  "items": [
                    {
                      "type": "Image",
                      "url": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/work_item/assets/circle.png",
                      "width": "8px",
                      "height": "8px",
                      "altText": "Red circle"
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
                      "text": "Blocked",
                      "wrap": true
                    }
                  ],
                  "spacing": "Small",
                  "verticalContentAlignment": "Center"
                },
                {
                  "type": "Column",
                  "width": "auto",
                  "items": [
                    {
                      "type": "TextBlock",
                      "text": "|",
                      "wrap": true
                    }
                  ],
                  "spacing": "Small",
                  "verticalContentAlignment": "Center"
                },
                {
                  "type": "Column",
                  "width": "auto",
                  "items": [
                    {
                      "type": "TextBlock",
                      "text": "Hugo Gonzalez",
                      "wrap": true
                    }
                  ],
                  "spacing": "Small",
                  "verticalContentAlignment": "Center"
                }
              ]
            }
          ]
        }
      ]
    },
    {
      "type": "ColumnSet",
      "targetWidth": "atLeast:narrow",
      "columns": [
        {
          "type": "Column",
          "width": "auto",
          "items": [
            {
              "type": "Image",
              "url": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/work_item/assets/circle.png",
              "width": "8px",
              "height": "8px",
              "altText": "Red circle"
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
              "text": "Blocked",
              "wrap": true
            }
          ],
          "spacing": "Small",
          "verticalContentAlignment": "Center"
        },
        {
          "type": "Column",
          "width": "auto",
          "items": [
            {
              "type": "TextBlock",
              "text": "|",
              "wrap": true
            }
          ],
          "spacing": "Small",
          "verticalContentAlignment": "Center"
        },
        {
          "type": "Column",
          "width": "auto",
          "items": [
            {
              "type": "TextBlock",
              "text": "Hugo Gonzalez",
              "wrap": true
            }
          ],
          "spacing": "Small",
          "verticalContentAlignment": "Center"
        }
      ]
    },
    {
      "type": "ActionSet",
      "actions": [
        {
          "type": "Action.OpenUrl",
          "title": "Open",
          "url": "https://adaptivecards.io/"
        },
        {
          "type": "Action.Submit",
          "title": "Follow",
          "iconUrl": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/work_item/assets/follow_icon.png"
        }
      ]
    }
  ]
}
```

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
      "type": "ColumnSet",
      "columns": [
        {
          "type": "Column",
          "width": "auto",
          "items": [
            {
              "type": "Image",
              "url": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/work_item/assets/thumb_image.png",
              "width": "56px",
              "height": "56px",
              "altText": "Logo"
            }
          ]
        },
        {
          "type": "Column",
          "width": "stretch",
          "items": [
            {
              "type": "TextBlock",
              "text": "Bug 2837 - Icons not rendering in dark mode",
              "wrap": true,
              "weight": "Bolder"
            },
            {
              "type": "ColumnSet",
              "targetWidth": "atLeast:narrow",
              "columns": [
                {
                  "type": "Column",
                  "width": "auto",
                  "items": [
                    {
                      "type": "Image",
                      "url": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/work_item/assets/circle.png",
                      "width": "8px",
                      "height": "8px",
                      "altText": "Red circle"
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
                      "text": "Blocked",
                      "wrap": true
                    }
                  ],
                  "spacing": "Small",
                  "verticalContentAlignment": "Center"
                },
                {
                  "type": "Column",
                  "width": "auto",
                  "items": [
                    {
                      "type": "TextBlock",
                      "text": "|",
                      "wrap": true
                    }
                  ],
                  "spacing": "Small",
                  "verticalContentAlignment": "Center"
                },
                {
                  "type": "Column",
                  "width": "auto",
                  "items": [
                    {
                      "type": "TextBlock",
                      "text": "Hugo Gonzalez",
                      "wrap": true
                    }
                  ],
                  "spacing": "Small",
                  "verticalContentAlignment": "Center"
                }
              ]
            }
          ]
        }
      ]
    },
    {
      "type": "ColumnSet",
      "targetWidth": "atLeast:narrow",
      "columns": [
        {
          "type": "Column",
          "width": "auto",
          "items": [
            {
              "type": "Image",
              "url": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/work_item/assets/circle.png",
              "width": "8px",
              "height": "8px",
              "altText": "Red circle"
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
              "text": "Blocked",
              "wrap": true
            }
          ],
          "spacing": "Small",
          "verticalContentAlignment": "Center"
        },
        {
          "type": "Column",
          "width": "auto",
          "items": [
            {
              "type": "TextBlock",
              "text": "|",
              "wrap": true
            }
          ],
          "spacing": "Small",
          "verticalContentAlignment": "Center"
        },
        {
          "type": "Column",
          "width": "auto",
          "items": [
            {
              "type": "TextBlock",
              "text": "Hugo Gonzalez",
              "wrap": true
            }
          ],
          "spacing": "Small",
          "verticalContentAlignment": "Center"
        }
      ]
    },
    {
      "type": "ActionSet",
      "actions": [
        {
          "type": "Action.OpenUrl",
          "title": "Open",
          "url": "https://adaptivecards.io/"
        },
        {
          "type": "Action.Submit",
          "title": "Follow",
          "iconUrl": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/work_item/assets/follow_icon.png"
        }
      ]
    }
  ]
}
````
