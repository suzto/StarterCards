### Card Payload

````
{
  "type": "AdaptiveCard",
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
                      "text": "|",
                      "wrap": true
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
                      "text": "Hugo Gonzalez",
                      "wrap": true
                    }
                  ],
                  "spacing": "Small"
                }
              ]
            }
          ]
        }
      ]
    },
    {
      "type": "ColumnSet",
      "targetWidth": "veryNarrow",
      "columns": [
        {
          "type": "Column",
          "width": "auto",
          "items": [
            {
              "type": "Image",
              "url": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/work_item/assets/circle.png",
              "width": "8px",
              "height": "8px"
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
              "text": "|",
              "wrap": true
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
              "text": "Hugo Gonzalez",
              "wrap": true
            }
          ],
          "spacing": "Small"
        }
      ]
    },
    {
      "type": "ActionSet",
      "actions": [
        {
          "type": "Action.OpenUrl",
          "title": "Open"
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

### Full width Card payload

````
{
  "type": "AdaptiveCard",
  "$schema": "http://adaptivecards.io/schemas/adaptive-card.json",
  "version": "1.5",
  "msTeams": {
    "width": "full"
  },
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
                      "text": "|",
                      "wrap": true
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
                      "text": "Hugo Gonzalez",
                      "wrap": true
                    }
                  ],
                  "spacing": "Small"
                }
              ]
            }
          ]
        }
      ]
    },
    {
      "type": "ColumnSet",
      "targetWidth": "veryNarrow",
      "columns": [
        {
          "type": "Column",
          "width": "auto",
          "items": [
            {
              "type": "Image",
              "url": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/work_item/assets/circle.png",
              "width": "8px",
              "height": "8px"
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
              "text": "|",
              "wrap": true
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
              "text": "Hugo Gonzalez",
              "wrap": true
            }
          ],
          "spacing": "Small"
        }
      ]
    },
    {
      "type": "ActionSet",
      "actions": [
        {
          "type": "Action.OpenUrl",
          "title": "Open"
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