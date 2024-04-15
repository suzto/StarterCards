# Communications

## Summary

The <b>Communications Card</b> is your gateway to vibrant social connectivity. Ideal for broadcasting company updates, sharing posts, or fostering community ties, this card is versatile enough to match your messaging. Enrich it with custom text, imagery, and links for an immersive social journey.

_bot-sent_ card example:

![picture alt](assets/CommunicationsCard.png)


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

![picture of the extension in action](assets/layouts.png)

## Inspiration Gallery

Below you'll find a few alternative expressions of the card.

![picture of alterations](assets/inspiration.png)
<br/><br/>





<a href="https://adaptivecards.io/designer?card=https%3A%2F%2Fraw.githubusercontent.com%2Fsuzto%2FStarterCards%2Fmain%2Fsamples%2Fcommunication%2Fcard.json" target="_blank">
  <img src="../../assets/open_designer_button.png" width="190" alt="Open in Adaptive Card Designer" />
</a>

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
  "speak": "Hawaii holiday escape deals start tonight",
  "body": [
    {
      "columns": [
        {
          "width": "auto",
          "items": [
            {
              "url": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/communication/assets/icon_megaphone.png",
              "height": "16px",
              "type": "Image",
              "altText": "Megaphone icon",
              "width": "16px"
            }
          ],
          "type": "Column"
        },
        {
          "width": "stretch",
          "items": [
            {
              "isSubtle": true,
              "size": "Small",
              "text": "Posted in Employee Deals",
              "wrap": true,
              "type": "TextBlock"
            }
          ],
          "spacing": "Small",
          "type": "Column"
        }
      ],
      "type": "ColumnSet",
      "targetWidth": "narrow"
    },
    {
      "columns": [
        {
          "width": "auto",
          "items": [
            {
              "url": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/communication/assets/avatar.png",
              "height": "auto",
              "type": "Image",
              "altText": "Avatar of Laurence Gibertson"
            }
          ],
          "type": "Column"
        },
        {
          "width": "stretch",
          "items": [
            {
              "text": "Laurence Gibertson",
              "weight": "Bolder",
              "wrap": true,
              "type": "TextBlock"
            },
            {
              "isSubtle": true,
              "size": "Small",
              "text": "Oct 22",
              "wrap": true,
              "spacing": "None",
              "type": "TextBlock"
            }
          ],
          "type": "Column"
        }
      ],
      "type": "ColumnSet",
      "targetWidth": "narrow"
    },
    {
      "columns": [
        {
          "width": "stretch",
          "items": [
            {
              "columns": [
                {
                  "width": "auto",
                  "items": [
                    {
                      "url": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/communication/assets/icon_megaphone.png",
                      "height": "16px",
                      "type": "Image",
                      "altText": "Megaphone icon",
                      "width": "16px"
                    }
                  ],
                  "type": "Column"
                },
                {
                  "width": "stretch",
                  "items": [
                    {
                      "isSubtle": true,
                      "size": "Small",
                      "text": "Posted in Employee Deals",
                      "wrap": true,
                      "type": "TextBlock"
                    }
                  ],
                  "spacing": "Small",
                  "type": "Column"
                }
              ],
              "targetWidth": "atLeast:standard",
              "type": "ColumnSet"
            },
            {
              "columns": [
                {
                  "width": "auto",
                  "items": [
                    {
                      "url": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/communication/assets/avatar.png",
                      "height": "auto",
                      "type": "Image",
                      "altText": "Avatar of Laurence Gibertson"
                    }
                  ],
                  "type": "Column"
                },
                {
                  "width": "stretch",
                  "items": [
                    {
                      "text": "Laurence Gibertson",
                      "weight": "Bolder",
                      "wrap": true,
                      "type": "TextBlock"
                    },
                    {
                      "isSubtle": true,
                      "size": "Small",
                      "text": "Oct 22",
                      "wrap": true,
                      "spacing": "None",
                      "type": "TextBlock"
                    }
                  ],
                  "type": "Column"
                }
              ],
              "targetWidth": "atLeast:standard",
              "type": "ColumnSet"
            },
            {
              "size": "Large",
              "text": "Hawaii holiday escape deals start tonight!",
              "weight": "Bolder",
              "wrap": true,
              "spacing": "Small",
              "type": "TextBlock"
            },
            {
              "text": "For a limited time, you can book a four night stay at luxury resort on the island of Maui for only $999 per person.",
              "wrap": true,
              "spacing": "Small",
              "type": "TextBlock",
              "maxLines": 3
            },
            {
              "columns": [
                {
                  "width": "auto",
                  "items": [
                    {
                      "horizontalAlignment": "Right",
                      "url": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/communication/assets/icon_like_outline.png",
                      "width": "16px",
                      "height": "16px",
                      "id": "likeOutline",
                      "type": "Image",
                      "altText": "Outlined thumbs up"
                    },
                    {
                      "horizontalAlignment": "Right",
                      "url": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/communication/assets/icon_like_filled.png",
                      "width": "16px",
                      "height": "16px",
                      "id": "likeFilled",
                      "isVisible": false,
                      "type": "Image",
                      "altText": "Thumbs up"
                    }
                  ],
                  "verticalContentAlignment": "Bottom",
                  "spacing": "None",
                  "type": "Column"
                },
                {
                  "width": "stretch",
                  "items": [
                    {
                      "size": "Small",
                      "text": "26 people like this",
                      "wrap": true,
                      "id": "commentLike",
                      "type": "TextBlock"
                    },
                    {
                      "size": "Small",
                      "text": "27 people like this",
                      "wrap": true,
                      "id": "commentUnlike",
                      "isVisible": false,
                      "type": "TextBlock"
                    }
                  ],
                  "verticalContentAlignment": "Bottom",
                  "spacing": "Small",
                  "type": "Column"
                }
              ],
              "height": "stretch",
              "spacing": "ExtraLarge",
              "type": "ColumnSet"
            },
            {
              "targetWidth": "atMost:narrow",
              "actions": [
                {
                  "targetElements": [
                    "likeFilled",
                    "likeOutline",
                    "commentLike",
                    "commentUnlike",
                    "likeFilled2",
                    "likeOutline2",
                    "commentLike2",
                    "commentUnlike2"
                  ],
                  "title": "Like",
                  "type": "Action.ToggleVisibility"
                },
                {
                  "title": "Comment",
                  "type": "Action.Submit"
                }
              ],
              "spacing": "Medium",
              "type": "ActionSet"
            }
          ],
          "type": "Column"
        },
        {
          "width": "auto",
          "items": [
            {
              "targetWidth": "atLeast:standard",
              "url": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/communication/assets/hero_image.png",
              "width": "150px",
              "height": "auto",
              "type": "Image",
              "altText": "Beach Image"
            },
            {
              "targetWidth": "narrow",
              "url": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/communication/assets/hero_image.png",
              "width": "100px",
              "height": "auto",
              "type": "Image",
              "altText": "Beach Image"
            },
            {
              "targetWidth": "atLeast:standard",
              "actions": [
                {
                  "targetElements": [
                    "likeFilled",
                    "likeOutline",
                    "commentLike",
                    "commentUnlike",
                    "likeFilled2",
                    "likeOutline2",
                    "commentLike2",
                    "commentUnlike2"
                  ],
                  "title": "Like",
                  "type": "Action.ToggleVisibility"
                },
                {
                  "title": "Comment",
                  "type": "Action.Submit"
                }
              ],
              "spacing": "Medium",
              "type": "ActionSet"
            }
          ],
          "type": "Column"
        }
      ],
      "type": "ColumnSet",
      "targetWidth": "atLeast:narrow"
    },
    {
      "type": "Container",
      "targetWidth": "veryNarrow",
      "items": [
        {
          "columns": [
            {
              "width": "auto",
              "items": [
                {
                  "url": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/communication/assets/icon_megaphone.png",
                  "height": "16px",
                  "type": "Image",
                  "altText": "Megaphone icon",
                  "width": "16px"
                }
              ],
              "type": "Column"
            },
            {
              "width": "stretch",
              "items": [
                {
                  "isSubtle": true,
                  "size": "Small",
                  "text": "Posted in Employee Deals",
                  "wrap": true,
                  "type": "TextBlock"
                }
              ],
              "spacing": "Small",
              "type": "Column"
            }
          ],
          "type": "ColumnSet"
        },
        {
          "columns": [
            {
              "width": "auto",
              "items": [
                {
                  "url": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/communication/assets/avatar.png",
                  "height": "auto",
                  "type": "Image",
                  "altText": "Avatar of Laurence Gibertson"
                }
              ],
              "type": "Column"
            },
            {
              "width": "stretch",
              "items": [
                {
                  "text": "Laurence Gibertson",
                  "weight": "Bolder",
                  "wrap": true,
                  "type": "TextBlock"
                },
                {
                  "isSubtle": true,
                  "size": "Small",
                  "text": "Oct 22",
                  "wrap": true,
                  "spacing": "None",
                  "type": "TextBlock"
                }
              ],
              "type": "Column"
            }
          ],
          "type": "ColumnSet"
        },
        {
          "size": "Large",
          "text": "Hawaii holiday escape deals start tonight!",
          "weight": "Bolder",
          "wrap": true,
          "spacing": "Small",
          "type": "TextBlock"
        },
        {
          "columns": [
            {
              "width": "stretch",
              "items": [
                {
                  "maxLines": 4,
                  "text": "For a limited time, you can book a four night stay at luxury resort on the island of Maui for only $999 per person.",
                  "wrap": true,
                  "spacing": "Small",
                  "type": "TextBlock"
                }
              ],
              "type": "Column"
            },
            {
              "width": "auto",
              "items": [
                {
                  "url": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/communication/assets/hero_image.png",
                  "width": "60px",
                  "type": "Image"
                }
              ],
              "type": "Column"
            }
          ],
          "type": "ColumnSet"
        },
        {
          "columns": [
            {
              "width": "auto",
              "items": [
                {
                  "horizontalAlignment": "Right",
                  "url": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/communication/assets/icon_like_outline.png",
                  "width": "16px",
                  "height": "16px",
                  "id": "likeOutline2",
                  "type": "Image",
                  "altText": "Outlined thumbs up"
                },
                {
                  "horizontalAlignment": "Right",
                  "url": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/communication/assets/icon_like_filled.png",
                  "width": "16px",
                  "height": "16px",
                  "id": "likeFilled2",
                  "isVisible": false,
                  "type": "Image",
                  "altText": "Thumbs up"
                }
              ],
              "verticalContentAlignment": "Center",
              "spacing": "None",
              "type": "Column"
            },
            {
              "width": "stretch",
              "items": [
                {
                  "size": "Small",
                  "text": "26 people like this",
                  "wrap": true,
                  "id": "commentLike2",
                  "type": "TextBlock"
                },
                {
                  "size": "Small",
                  "text": "27 people like this",
                  "wrap": true,
                  "id": "commentUnlike2",
                  "isVisible": false,
                  "type": "TextBlock"
                }
              ],
              "verticalContentAlignment": "Center",
              "spacing": "Small",
              "type": "Column"
            }
          ],
          "spacing": "ExtraLarge",
          "type": "ColumnSet"
        },
        {
          "actions": [
            {
              "targetElements": [
                "likeFilled",
                "likeOutline",
                "commentLike",
                "commentUnlike",
                "likeFilled2",
                "likeOutline2",
                "commentLike2",
                "commentUnlike2"
              ],
              "title": "Like",
              "type": "Action.ToggleVisibility"
            },
            {
              "title": "Comment",
              "type": "Action.Submit"
            }
          ],
          "spacing": "Medium",
          "type": "ActionSet"
        }
      ]
    }
  ],
  "$schema": "http://adaptivecards.io/schemas/adaptive-card.json",
  "version": "1.5"
}
```

</details>

*To create a "full width" card, add the following code to the JSON.* <br>

```json
"msTeams": {
    "width": "full"
  },
```
