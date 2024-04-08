# Communication 

`need to update this page`

![picture alt](assets/CommsCard.png)

### Card Payload

````
{
  "type": "AdaptiveCard",
  "body": [
    {
      "columns": [
        {
          "width": "auto",
          "items": [
            {
              "url": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/communication/assets/icon_megaphone.png",
              "height": "auto",
              "type": "Image",
              "altText": "📢"
            }
          ],
          "type": "Column"
        },
        {
          "width": "stretch",
          "items": [
            {
              "isSubtle": true,
              "size": "small",
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
              "altText": "Avatar"
            }
          ],
          "type": "Column"
        },
        {
          "width": "stretch",
          "items": [
            {
              "text": "Laurence Gibertson",
              "weight": "bolder",
              "wrap": true,
              "type": "TextBlock"
            },
            {
              "isSubtle": true,
              "size": "small",
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
                      "height": "auto",
                      "type": "Image",
                      "altText": "📢"
                    }
                  ],
                  "type": "Column"
                },
                {
                  "width": "stretch",
                  "items": [
                    {
                      "isSubtle": true,
                      "size": "small",
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
                      "altText": "Avatar"
                    }
                  ],
                  "type": "Column"
                },
                {
                  "width": "stretch",
                  "items": [
                    {
                      "text": "Laurence Gibertson",
                      "weight": "bolder",
                      "wrap": true,
                      "type": "TextBlock"
                    },
                    {
                      "isSubtle": true,
                      "size": "small",
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
              "size": "large",
              "text": "Hawaii holiday escape deals start tonight!",
              "weight": "bolder",
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
                      "horizontalAlignment": "right",
                      "url": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/communication/assets/icon_like_outline.png",
                      "height": "auto",
                      "id": "likeOutline",
                      "type": "Image",
                      "altText": "👍"
                    },
                    {
                      "horizontalAlignment": "right",
                      "url": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/communication/assets/icon_like_filled.png",
                      "height": "auto",
                      "id": "likeFilled",
                      "isVisible": false,
                      "type": "Image",
                      "altText": "👍"
                    }
                  ],
                  "verticalContentAlignment": "center",
                  "spacing": "None",
                  "type": "Column"
                },
                {
                  "width": "stretch",
                  "items": [
                    {
                      "size": "small",
                      "text": "26 people like this",
                      "wrap": true,
                      "id": "commentLike",
                      "type": "TextBlock"
                    },
                    {
                      "size": "small",
                      "text": "27 people like this",
                      "wrap": true,
                      "id": "commentUnlike",
                      "isVisible": false,
                      "type": "TextBlock"
                    }
                  ],
                  "verticalContentAlignment": "center",
                  "spacing": "Small",
                  "type": "Column"
                }
              ],
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
                    "commentUnlike"
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
                    "commentUnlike"
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
                  "url": "https://us-prod.asyncgw.teams.microsoft.com/urlp/v1/url/content?url=https://raw.githubusercontent.com/suzto/StarterCards/main/samples/communication/assets/icon_megaphone.png",
                  "height": "auto",
                  "type": "Image"
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
                  "type": "Image"
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
                  "height": "auto",
                  "id": "likeOutline",
                  "type": "Image"
                },
                {
                  "horizontalAlignment": "Right",
                  "url": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/communication/assets/icon_like_filled.png",
                  "height": "auto",
                  "id": "likeFilled",
                  "isVisible": false,
                  "type": "Image"
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
                "commentUnlike"
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
````

### Full width Card Payload

````
{
  "type": "AdaptiveCard",
  "msTeams": {
    "width": "full"
  },
  "body": [
    {
      "columns": [
        {
          "width": "auto",
          "items": [
            {
              "url": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/communication/assets/icon_megaphone.png",
              "height": "auto",
              "type": "Image",
              "altText": "📢"
            }
          ],
          "type": "Column"
        },
        {
          "width": "stretch",
          "items": [
            {
              "isSubtle": true,
              "size": "small",
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
              "altText": "Avatar"
            }
          ],
          "type": "Column"
        },
        {
          "width": "stretch",
          "items": [
            {
              "text": "Laurence Gibertson",
              "weight": "bolder",
              "wrap": true,
              "type": "TextBlock"
            },
            {
              "isSubtle": true,
              "size": "small",
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
                      "height": "auto",
                      "type": "Image",
                      "altText": "📢"
                    }
                  ],
                  "type": "Column"
                },
                {
                  "width": "stretch",
                  "items": [
                    {
                      "isSubtle": true,
                      "size": "small",
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
                      "altText": "Avatar"
                    }
                  ],
                  "type": "Column"
                },
                {
                  "width": "stretch",
                  "items": [
                    {
                      "text": "Laurence Gibertson",
                      "weight": "bolder",
                      "wrap": true,
                      "type": "TextBlock"
                    },
                    {
                      "isSubtle": true,
                      "size": "small",
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
              "size": "large",
              "text": "Hawaii holiday escape deals start tonight!",
              "weight": "bolder",
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
                      "horizontalAlignment": "right",
                      "url": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/communication/assets/icon_like_outline.png",
                      "height": "auto",
                      "id": "likeOutline",
                      "type": "Image",
                      "altText": "👍"
                    },
                    {
                      "horizontalAlignment": "right",
                      "url": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/communication/assets/icon_like_filled.png",
                      "height": "auto",
                      "id": "likeFilled",
                      "isVisible": false,
                      "type": "Image",
                      "altText": "👍"
                    }
                  ],
                  "verticalContentAlignment": "center",
                  "spacing": "None",
                  "type": "Column"
                },
                {
                  "width": "stretch",
                  "items": [
                    {
                      "size": "small",
                      "text": "26 people like this",
                      "wrap": true,
                      "id": "commentLike",
                      "type": "TextBlock"
                    },
                    {
                      "size": "small",
                      "text": "27 people like this",
                      "wrap": true,
                      "id": "commentUnlike",
                      "isVisible": false,
                      "type": "TextBlock"
                    }
                  ],
                  "verticalContentAlignment": "center",
                  "spacing": "Small",
                  "type": "Column"
                }
              ],
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
                    "commentUnlike"
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
                    "commentUnlike"
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
                  "url": "https://us-prod.asyncgw.teams.microsoft.com/urlp/v1/url/content?url=https://raw.githubusercontent.com/suzto/StarterCards/main/samples/communication/assets/icon_megaphone.png",
                  "height": "auto",
                  "type": "Image"
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
                  "type": "Image"
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
                  "height": "auto",
                  "id": "likeOutline",
                  "type": "Image"
                },
                {
                  "horizontalAlignment": "Right",
                  "url": "https://raw.githubusercontent.com/suzto/StarterCards/main/samples/communication/assets/icon_like_filled.png",
                  "height": "auto",
                  "id": "likeFilled",
                  "isVisible": false,
                  "type": "Image"
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
                "commentUnlike"
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
````